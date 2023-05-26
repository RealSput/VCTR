# VCTR
Runtime vector for Geometry Dash using SPWN

# Usage
### Creating a brand-new array
```ts
// Create brand-new vector with a maximum length
vec = @vctr::create(5);

// Display vector
vec.display(15, 15);

// Add values
vec.display(1);
vec.display(2);
vec.display(3);

// Wait 500 ms and pop value from vector
wait(0.5);
vec.pop();
```
### Create vector from existing array
```ts
vec = @vctr::from([1, 2, 3, 4, 5]);

wait(0.5);
vec.pop();
```
