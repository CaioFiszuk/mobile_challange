# Mobile_challange
### It is a simple and responsive web page
-------------------------------------------
I have learned:

- To use the **@keyframes** to create a CSS animation
```
@keyframes topdown {
    0%{
        opacity: 0;
        transform: translateY(-40px);
     }
 
     100%{
        opacity: 1;
        transform: translateY(0);
     }
}
```

- To use the **@media** to create a mobile application based on the screen width and the priority of the mobile **(Mobile First)**
```
@media(min-width: 500px){
    body{
        display: flex;
        gap: 9.8rem;
    }

    header{
        width: 37.7rem;
        height: 72.0rem;
    }
}
```

- The pseudo classes **:nth-child**, **:first-child**, **:last-child**
  ```
    a:nth-child(2){
         text-decoration:none;
      }
  ```

- The variables in CSS
  ```
     :root{
    --bg-header: #8e9aaf;
  }

  header{
    background-color: var(--bg-header);
  }
```
