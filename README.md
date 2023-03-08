# Draggable site

Template with gsap draggable and inertia plugin. 

## Key takeaways

- **Stylization of body so that the unit occupies the entire space and is covered**

```css
overflow: hidden;
height: 100vh;
```

- **Creating a tile maison**

```css
.gallery {
  width: 30vw;
  column-width: 2em;
  transform: scale(8.2);
}
```

- **Connection draggable and inertia**

>
```javascript
Draggable.create(".gallery", {
  bounds: "body",
  inertia: true,
})
```
## Screenshot
![ezgif com-video-to-gif-4](https://user-images.githubusercontent.com/113831614/223711821-477f1b7f-2c2b-42cd-a33a-92d39b0f6a3c.gif)



