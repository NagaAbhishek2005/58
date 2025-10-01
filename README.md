*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
} 

body{
    font-family: 'Courier New', Courier, monospace;
}
nav{
    background-color: cyan;
    color: blueviolet;
    padding: 10px 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.logo{
    font-size: 1.5rem;
    font-weight: bold;
}
#menu-toggle{
    display: none;
}
.menu-icon{
    display: none;
    font-size: 1.8rem;
    cursor: pointer;
    user-select: none;
}
.nav-links{
    list-style: none;
    display: flex;
    gap: 20px;
}
.nav-links li a{
    text-decoration: none;
    color: blue;
    font-size: 1ren;
    transition: color 0.3s ease;
}
.nav-links li a:hover{
    color: blueviolet;
}
