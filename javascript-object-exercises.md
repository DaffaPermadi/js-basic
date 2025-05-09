
# JavaScript Basic Object Exercises

Practice working with objects in JavaScript with the following exercises.

---

## 1. Create an Object

Create an object called `person` with these properties:

| Key   | Value       |
|-------|-------------|
| name  | "John"      |
| age   | 25          |
| job   | "Developer" |

```javascript
Person = {
    name: "John",
    age: 25,
    job: "Developer"
}
```

---

## 2. Access Object Properties

Use `console.log` to display:
- The person's name
- The person's job

```javascript
console.log(Person.name); 
console.log(Person.job);
```

---

## 3. Add New Property

Add a new property called `hobby` with value `"Reading"` to the `person` object.

```javascript
Person.hobby = "Reading";
```

---

## 4. Update Property

Change the `age` of `person` to `30`.

```javascript
Person.age = 30;
```

---

## 5. Delete Property

Remove the `job` property from the `person` object.

```javascript
delete Person.job;
```

---

## 6. Object Inside Object

Create an object `student` with:

| Key     | Value              |
|---------|-------------------|
| name    | "Alice"           |
| grade   | 90                |
| address | object with:      |
| - city  | "Jakarta"         |
| - country | "Indonesia"     |

Print `student`'s city.

```javascript
let Student = {
    name: "Alice",
    grade: 90,
    address: {
        city: "Jakarta",
        country: "Indonesia"
    }
}
```

---

## 7. Function in Object

Add a method called `greet` inside `person` object that returns:

> "Hi, my name is John"

Then call it.

```javascript
Person.greet = function(){
    return `Hi, my name is ${this.name}`
}
```

---

Happy Coding! 🚀
