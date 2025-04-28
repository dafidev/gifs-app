# 📸 GifsApp

This project is a simple GIF search application built with **Angular 19**.  
It allows users to **browse trending GIFs**, **search for GIFs by keywords**, and **view a history of their searches**.

## 🚀 Features

- Display trending GIFs on the dashboard.
- Search for GIFs by custom keywords.
- Keep a **search history** to easily revisit previous queries.
- Responsive layout using **Tailwind CSS**.
- Optimized with **Standalone Components** and **Signals**.
- API calls handled with **RxJS** and **HttpClient**.
- Dynamic routing with **RouterLink** and **RouterOutlet**.

## ⚙️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/dafidev/gifs-app.git
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

## 🛠️ Development server

To start a local server:

```bash
ng serve
```

Then open your browser at:

```
http://localhost:4200/
```

The app will automatically reload if you change any source files.

## 🧹 Project structure

- `/src/app/gifs/pages`: Application pages (dashboard, search, trending, history).
- `/src/app/gifs/components`: Reusable components like `GifList` and `SideMenu`.
- `/src/app/gifs/services`: Service to interact with the **Giphy API**.
- `/src/app/gifs/interfaces`: TypeScript interfaces for API responses.
- `/src/app/gifs/mapper`: Helper class to map API responses to usable GIF models.

## 🧪 Testing

To run unit tests:

```bash
ng test
```

_Note:_ Unit testing coverage is not included in this version.

## 📺 Build

To build the project for production:

```bash
ng build
```

Files will be generated inside `/dist`.

## 🔗 Useful Commands

- Generate a new component:
  ```bash
  ng generate component component-name
  ```
- Generate a new service:
  ```bash
  ng generate service service-name
  ```
- List available schematics:
  ```bash
  ng generate --help
  ```

## 📚 Additional Resources

- [Angular Documentation](https://angular.dev/)
- [Angular CLI Overview](https://angular.dev/tools/cli)
- [Giphy API Documentation](https://developers.giphy.com/docs/api/)

# 🌟 Final Notes

- Focuses heavily on best practices like **modular architecture**, **signals**, **computed properties**, and **rxjs patterns**.
