<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
      body {
        height: 100vh;
        display: flex;
        align-items: center;
        justify-content: center;
        margin: 0;
        font-family: sans-serif;
      }
      ul {
        margin: 0;
        padding: 0;
        display: flex;
        list-style-type: none;
      }
      ul li a {
        display: block;
        width: 120px;
        height: 40px;
        line-height: 40px;
        text-align: center;
        color: #262626;
        text-transform: capitalize;
        text-decoration: none;
        position: relative;
        transition: all 0.5s;
      }
      a:hover{
        color: #fff;
      }
      ul li span {
        position: absolute;
        width: 100%;
        height: 25%;
        background-color: #262626;
        z-index: -1;
        left: 0;
        top: 0;
        transform: scaleX(0);
        transition: all .5s;
        transform-origin: left;
      }
      ul li a:hover span{
        transform: scaleX(1);
      }
      span:nth-child(2){
        top: 25%;
        transition-delay: .15s;
      }
      span:nth-child(3){
        top: 50%;
        transition-delay: .3s;
      }
      span:nth-child(4){
        top: 75%;
        transition-delay: .45s;

      }
    </style>
  </head>
  <body>
    <ul>
      <li>
        <a href="#">
          <span></span>
          <span></span>
          <span></span>
          <span></span>home
        </a>
      </li>
      <li>
        <a href="#"
          ><span></span>
          <span></span>
          <span></span>
          <span></span>about</a
        >
      </li>
      <li>
        <a href="#"
          ><span></span>
          <span></span>
          <span></span>
          <span></span> services</a
        >
      </li>
      <li>
        <a href="#"
          ><span></span>
          <span></span>
          <span></span>
          <span></span> team</a
        >
      </li>
      <li>
        <a href="#"
          ><span></span>
          <span></span>
          <span></span>
          <span></span> contact</a
        >
      </li>
    </ul>
  </body>
</html>
