

# AGO: Artwork Monitor  
<img src="images/favicon.ico" alt="AGO Logo" width="50" height="50">

**Website:** [AGO](http://13.201.123.166:3000)  
**Strapi Admin:** [AGO Admin](http://13.201.123.166:3001/)

## Project Overview

**AGO** is an innovative, beacon-based art gallery management system designed to provide a personalized and interactive experience for users, while offering valuable insights for gallery administrators. This system leverages the power of **beacon technology** to track user engagement with artworks, capturing emotional responses (through heart rate) and proximity data (using RSSI). It then processes the collected data to generate detailed, personalized reports for users and provides valuable statistical insights for gallery owners.


## Demo Video

Here’s a demo video showcasing the functionality of the **AGO** system:

[![AGO Demo Video](https://img.youtube.com/vi/your-thumbnail-image-url-here/maxresdefault.jpg)](client-demo.mp4)

You can watch the demo by clicking the video above or by accessing the `client-demo.mp4` file directly in the repository.


## Project Features

- **Beacon Integration**: Each artwork in the gallery is assigned a beacon device to track user interactions based on proximity (RSSI) and heart rate.
- **Personalized User Experience**: Users can register via a Next.js portal and interact with the art gallery through custom devices like watches or cards.
- **Data Collection**: Interaction data (RSSI and heart rate) is collected when users are near artworks and stored in JSON format.
- **Data Processing**: The collected data is processed and used to generate personalized reports for users, providing insights on art preferences and emotional responses.
- **User Reports**: Reports are automatically generated and emailed to users with insights into their interactions and "persona" based on their preferences.
- **Statistical Insights**: Gallery administrators can access aggregated data, such as popular artworks, user trends, and overall engagement statistics.
- **Personalized Recommendations**: Based on user data, the system recommends artworks that align with each user's persona.


## How It Works

### User Interaction
Users are able to **self-register** via a **Next.js-based portal**, where they create profiles and register their devices for seamless interactions in the gallery. Upon entering the gallery, users can freely explore the space while their devices interact with the beacons assigned to each piece of art. Each time a user comes into range of a beacon, the system records data such as the **duration** of interaction with a particular artwork, the **distance** (using RSSI) from the artwork, and the **user's heart rate**, which is used to assess emotional responses to the art. This data collection provides galleries with detailed insights into the preferences, emotional engagement, and behaviors of their visitors.

### Data Collection & Processing
All interaction data is stored in **JSON format** and uploaded to the AGO system. The data includes **user proximity (RSSI)** and **heart rate**, both of which are key indicators of user engagement. This data is then processed by the system, which analyzes it to identify patterns in user behavior. For example, if a user consistently spends more time near a particular piece or shows a heightened emotional response (measured via heart rate), the system flags that artwork as a favorite for that user.

The processed data is used to generate **personalized reports** for each user. These reports contain insights into the user’s preferences, including which art pieces they were most engaged with, what their emotional responses were, and which persona best represents their tastes. Additionally, these reports are **automatically sent to users via email**, providing them with a unique, data-driven understanding of their experience in the gallery.

### Personalized Recommendations
One of the standout features of AGO is its ability to create **personalized recommendations** for users based on their interaction data. The system categorizes users into different **personas** based on their engagement and emotional responses, and suggests new artworks that align with their preferences. This ensures that users always have new and relevant pieces to explore in the gallery, enhancing their overall experience.

### Gallery Analytics
In addition to user reports, AGO also offers valuable statistical insights for gallery administrators. The data collected from user interactions allows the system to generate **analytics** on a variety of key metrics, such as:
- **Most engaging artworks**: Identifying the art pieces that attract the most attention and emotional response from visitors.
- **User engagement trends**: Tracking how long visitors spend interacting with the gallery and which areas attract the most traffic.
- **Persona-based insights**: Understanding the demographics and preferences of visitors, allowing for better-targeted marketing and exhibit planning.

This rich dataset enables gallery owners and curators to make more informed decisions about exhibit placements, marketing campaigns, and future curations, based on the real-world preferences and behaviors of their visitors.


## System Architecture

AGO is built using **Next.js** for the frontend, providing a fast, dynamic, and responsive user interface for users to register, track interactions, and access personalized reports. The backend is powered by **Strapi CMS**, a flexible and headless content management system that handles user data, artwork details, and beacon interactions. The system allows gallery administrators to manage artwork details, track user interactions, and gain insights from the data collected through the beacons.

The integration of **BLE beacon technology** enables real-time tracking of users as they interact with artworks, while the backend processes and analyzes the data to create meaningful insights for both the users and gallery administrators. The user registration process, personalized report generation, and recommendation engine are all powered by the combination of **Next.js** for the frontend and **Strapi CMS** for backend management.

## Use Cases

- **Art Galleries**: AGO helps galleries improve customer engagement by offering a personalized experience for visitors, making art exploration more interactive and insightful.
- **Museums & Exhibitions**: Museums can use AGO to gather data on how visitors engage with exhibits, track emotional responses, and adjust exhibits based on visitor preferences.
- **Art Collectors & Enthusiasts**: Individual users or art collectors can explore their personalized reports to gain a deeper understanding of their art preferences and receive recommendations for future acquisitions.


## Future Enhancements

- **Augmented Reality (AR) Integration**: Enhancing the user experience by integrating AR to provide interactive, real-time details about the art pieces they are engaging with.
- **Advanced AI for Personalization**: Implementing AI-driven algorithms to create even more accurate and dynamic artwork recommendations based on user interaction history.
- **Cross-Platform Compatibility**: Extending support for other devices such as smartphones or smart glasses to further enrich the user experience.
- **Data Visualization for Admins**: Adding more advanced data visualization features in the admin panel to help gallery owners make real-time decisions based on live data.

## Images
<img src="images/Front Screen 1.png" alt="Front Screen 1.png" style="width: 100%;border-radius:8px;">
<img src="images/Front Screen 2.png" alt="Front Screen 2.png" style="width: 100%;border-radius:8px;">
<img src="images/Front Screen 3.png" alt="Front Screen 3.png" style="width: 100%;border-radius:8px;">
<img src="images/Front Screen 4.png" alt="Front Screen 4.png" style="width: 100%;border-radius:8px;">
<img src="images/Front Screen 5.png" alt="Front Screen 5.png" style="width: 100%;border-radius:8px;">
<img src="images/Front Screen 6.png" alt="Front Screen 6.png" style="width: 100%;border-radius:8px;">
<img src="images/Artwork Create.png" alt="Artwork Create.png" style="width: 100%;border-radius:8px;">
<img src="images/Artwork list.png" alt="Artwork list.png" style="width: 100%;border-radius:8px;">
<img src="images/Becons Add.png" alt="Becons Add.png" style="width: 100%;border-radius:8px;">
<img src="images/Becons List.png" alt="Becons List.png" style="width: 100%;border-radius:8px;">
<img src="images/Color Era Create.png" alt="Color Era Create.png" style="width: 100%;border-radius:8px;">
<img src="images/Color Era List.png" alt="Color Era List.png" style="width: 100%;border-radius:8px;">
<img src="images/Device Create.png" alt="Device Create.png" style="width: 100%;border-radius:8px;">
<img src="images/Login admin.png" alt="Login admin.png" style="width: 100%;border-radius:8px;">
<img src="images/Upload Record json.png" alt="Upload Record json.png" style="width: 100%;border-radius:8px;">
<img src="images/Upload Records json data.png" alt="Upload Records json data.png" style="width: 100%;border-radius:8px;">
