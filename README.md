# Netflix GPT - AI Movie Recommendation Platform

An OTT platform inspired by Netflix that fetches movie data, provides AI-driven recommendations, and enhances user experience with advanced features.

---

## **Features**

### **Public Access**
- **SignIn/SignUp Page**
   - User authentication for secure access.
   - Validations handled efficiently with **Formik** and React's `useRef` hook.
- **Search Bar**
   - Multilingual search functionality using **TMDB API**.
   - Implemented memoization to minimize unnecessary server calls and improve performance.

### **Authenticated Access**
- **Home Page**
   - Browse the latest movies and trending shows.
   - Responsive UI designed with **Tailwind CSS**.
- **Browse Page**
   - **Navbar**: Easy navigation across sections.
   - **Showcase Section**: Highlights popular titles.
   - **Trending Movies**: AI-powered suggestions.
   - **Movie Lists**: Multiple categorized movie sections.
- **AI-Powered NetflixGPT**
   - Smart movie recommendations based on user inputs and preferences.

---

## **Tech Stack**

| **Tech**                | **Purpose**                               |
|-------------------------|-------------------------------------------|
| **React.js**            | Component-based frontend development.    |
| **Redux**               | State management for fetched movie data. |
| **Formik**              | Input validation and error handling.     |
| **Tailwind CSS**        | Fast and modern responsive UI styling.   |
| **TMDB API**            | Movie data fetching and integration.     |
| **React Hooks**         | Navigation (`useNavigate`), references, and performance optimization. |

---

## **Working of the Project**

1. **User Authentication**  
   - Users must sign up/sign in to access the browsing and recommendation features.  

2. **Movie Search**  
   - Search for movies or shows using the **TMDB API**.  
   - Multilingual support and memoized requests for better performance.

3. **AI Recommendations**  
   - NetflixGPT offers personalized suggestions using AI.

4. **Movie Listings**  
   - Browse categorized movies: Trending, Recommendations, and Custom Lists.  

5. **Error Handling**  
   - Input forms are validated with Formik, ensuring smooth user experience.  
