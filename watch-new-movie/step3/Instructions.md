1. `.movie` class is for movie detail.

```css
.movie {
  width: 28rem;
  margin: 1.9rem;
  background-color: var(--secondary_color);
  box-shadow: 0.2rem 0.2rem 3rem 0 rgba(0, 0, 0, 0.2);
  border-radius: 0.3rem;
  overflow: hidden;
  position: relative;
}
```

2.

```css
.movie-img {
  width: 100%;
}
```

3.

```css
.movie-info {
  display: flex;
  justify-content: space-between;
  padding: 0.8rem;
  letter-spacing: 0.1rem;
  font-size: 1.6rem;
}
```

4. The span tag class will change as per rating which will come form the APIs

```css
.movie-info h3 {
  color: #eee;
}

.movie-info span {
  background-color: var(--primary_color);
  padding: 0.5rem 0.5rem 0.5rem;
  border-radius: 0.5rem;
  font-weight: bold;
}
```

5.

```css
.movie-info span.green {
  color: lightgreen;
}

.movie-info span.red {
  color: crimson;
}

.movie-info span.orange {
  color: orange;
}
```

6.

```css
.overview {
  background-color: white;
  padding: 0.8em 0.8em;
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  max-width: 100%;
  transform: translateY(101%);
  font-size: 1.8rem;
  color: #a8a29e;
  transition: all 0.2s ease;
  box-shadow: 0.2rem 0.2rem 1rem rgba(0, 0, 0, 0.2);
}
```

7.

```css
transform: translateY(0);
```
