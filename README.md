// app.js
function greetUser() {
    console.log("Welcome to our app!");
}

// app.js
function greetUser(username) {
    if (username) {
        console.log(`Welcome back, ${username}!`);
    } else {
        console.log("Welcome to our app!");
    }
}

function login(username, password) {
    // simple mock authentication
    if (username === "admin" && password === "1234") {
        return true;
    }
    return false;
}
