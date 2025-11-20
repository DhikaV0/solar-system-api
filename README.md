# Solar System API

A simple API based on **static JSON** to display data about the Sun, planets, and natural satellites.
This API was created as a personal project for learning, visualization, and integration with front-end

## -Endpoint

All data is available in a single JSON file:

```
https://dhikav0.github.io/solar-system-api/solar-system.json
```

## -How to Use

### **Fetch with JavaScript / Next.js**

```js
const res = await fetch(
  "https://username.github.io/solar-system-api/solar-system.json"
);
const data = await res.json();

console.log(data.solar_system.planets);
```

### **Fetch with cURL**

```bash
curl https://username.github.io/solar-system-api/solar-system.json
```

## -License

All data is informative/educational and free to use.
If you use this project, please include a simple attribution (optional but appreciated).

## -Contribution

Pull requests for adding planet or satellite data, or updating descriptions, are welcome.

## -Goals of project

* Provides a lightweight static API about the Solar System.
* Serves as a simple backend for 3D/parallax visual projects.
* Serves as an exercise in creating a serverless JSON-based API.

## -Contact

If you have any questions, open an issue or contact us via GitHub.

> "Exploring our solar system on one JSON"
