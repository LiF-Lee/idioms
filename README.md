# idioms

```javascript
const fs = require("fs");
const json = JSON.parse(fs.readFileSync("idioms.json", "utf8"));

let Q = json["idioms"][0]["Q"];
let A = json["idioms"][0]["A"];

console.log(Q); // 呵呵大笑 (가가대소)
console.log(A); // 우스워서 소리를 크게 내어 웃음
```

# Download
* [Google Drive](https://drive.google.com/file/d/1ZoiyiDxkCr7BMhFINIuIB35Dv9IdkpjV/view?usp=drivesdk)
