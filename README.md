# Movie Mania

## Project Description

Movie Mania is a web application that allows users to search for movies using the OMDb API and submit a form with their favorite movies. The submitted forms are stored in a MongoDB database.

## Setup Instructions

1. **Clone the Repository**
    ```sh
    git clone https://github.com/MobinAkhter/MobinAkhterSoftwareDevAssessment.git
    cd MobinAkhterSoftwareDevAssessment
    ```

2. **Install Dependencies for the API**
    ```sh
    cd backend
    npm install
    ```

3. **Start the API Server**
    ```sh
    node src/server.js
    ```

4. **Install Dependencies for the Web Application**
    ```sh
    cd frontend
    npm install
    ```

5. **Start the Web Application**
    ```sh
    npm start
    ```

6. **Open Your Browser and Navigate to**
    ```
    http://localhost:3001
    ```

## Usage Instructions

- **Search for Movies**: Enter a movie name in the search bar and click "Search".
- **Submit a Form**: Fill out the form with your name, email, and favorite movie, then click "Submit".
- **View Submitted Forms**: Submitted forms will appear below the form submission area.
- **Edit/Delete Forms**: Use the "Edit" and "Delete" buttons to manage your submissions.
- **Pagination**: Use the numbered buttons to view additional submitted forms.
- **Switch Themes**: Use the "Dark Mode" button to switch to dark mode.

## Screenshots

### Home Page

![image](https://github.com/Canadian-Sheep-Federation/CSFIntershipAssessment2024/assets/55329336/fc644119-7514-4f0b-97f6-a2a900a43ab2)

### Search Results

![image](https://github.com/Canadian-Sheep-Federation/CSFIntershipAssessment2024/assets/55329336/9059cc0e-5da2-43ea-b362-cadf473d3bb9)

### Submit Form

![image](https://github.com/Canadian-Sheep-Federation/CSFIntershipAssessment2024/assets/55329336/bdd564a0-1f36-4f65-b7c3-96aab99c7b66)

### View Forms

![image](https://github.com/Canadian-Sheep-Federation/CSFIntershipAssessment2024/assets/55329336/8ed49a7f-9b5d-4898-8657-aa80690d6dc1)

### Edit Form

![image](https://github.com/Canadian-Sheep-Federation/CSFIntershipAssessment2024/assets/55329336/49ab13de-a4aa-4cf9-8716-81832c39bbb9)

### Dark Mode

![image](https://github.com/Canadian-Sheep-Federation/CSFIntershipAssessment2024/assets/55329336/ad626f90-15ff-4533-86bc-4f5731831e10)

![image](https://github.com/Canadian-Sheep-Federation/CSFIntershipAssessment2024/assets/55329336/31aec914-3e56-47d0-bbf5-a4a5076805db)

## Extension and Improvement Ideas

- **User Authentication**: Add authentication to allow users to create accounts and save their favorite movies.
- **Advanced Search**: Implement advanced search options (e.g., filter by genre, year).

## Next steps: Deployment

- **Hosting**: Deploy the web application using services like Vercel or Netlify.
- **Backend**: Host the API on platforms like Heroku.
