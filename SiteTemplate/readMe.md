# Site-Template

Go to template site **[click me!](https://startbootstrap.com/previews/heroic-features)**

>use the variables for colors and border-radius to reuse whenever you need 

```css
:root{
    --primary-color: #212529;

    --primay-link-color: #fff;

    --secondry-link-color: rgba(255, 255, 255, 0.55);

    --navbar-hover-color: rgba(255, 255, 255, 0.75);

    --box-background-color: #F8F9FA;

    --border-radius: 0.5rem;
}

```

>to create card display
```css
.main {
    display: flex;
    flex-wrap: wrap;
    margin: 4rem auto;
    gap: 3rem;

}
.box{
  background-color: var(--box-background-color);
  border-radius: var(--border-radius);
  display: inline-block;
  flex: 40%;
  justify-content: center;
  text-align: center;
  align-items: center;
  padding: 2rem;


}

```

>responsive design *media-query*
```css
/*
| < 576px | xs |
| >=576px | small |
| >=768px | medium |
| >=992px | large |
| >=1200px | xl |
| >=1400px | 2xl | 
*/
/* Small devices (tablets, 768px and up) */
@media screen and (min-width: 768px) and (max-width: 992px) {


    .hero-section h1 {
        font-size: 2.4rem;

    }

    .hero-section p {
        font-size: 1.3rem;
        line-height: 1;
        word-spacing: 1px;

    }

}

```


---
## :sparkles:  *The things been used* :sparkles: 

- Flex, Flex Wrap, Gap, Flex-direction
- Variables
- @font-family
- responsive tasarım 
  
