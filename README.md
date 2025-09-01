* Server for  Blood Donation application 


#

# Purpose of the server: 
<h5> # The purpose of this server is to make a connection between database and the Blood Donation Application.</h5>


#
# Installation Steps: 
Got it 👍 You’re basically asking **how to run the server side of a MERN project**.
I’ll break it down step by step so you can easily follow:

---

## 🚀 Steps to Run MERN Server Side

### 1. Clone the Repository

```bash
git clone <repository-url>
```

Replace `<repository-url>` with the actual GitHub/GitLab repo link.

---

### 2. Go into the Project Folder

```bash
cd <folder-name>
```

Replace `<folder-name>` with the project folder name.

---

### 3. Install Dependencies

First, install all packages from `package.json`:

```bash
npm install
```

Then install the required server packages:

```bash
npm i express dotenv jsonwebtoken cors mongodb stripe body-parser nodemon
```

---

### 4. Setup Environment Variables

Create a `.env` file in your project root (same folder as `index.js` or `server.js`). Example:

### 5. Start the Server

If your entry file is `index.js`:

```bash
nodemon index.js
```

or if it’s `server.js`:

```bash
nodemon server.js
```

Now the backend will run at:

```
http://localhost:5000
```

---

### 6. Test the Server

* Open browser → `http://localhost:5000/`
* Or use **Postman/Thunder Client** to test API routes.

---

✅ That’s it! Your **MERN server side** is running.
The client side (React) usually runs separately with `npm run dev` or `npm start`.



