# Game Shop E-commerce with API Integration and Mobile Functionalities in OutSystems

This project was developed during the last two weeks of the lab with Professor Paulo Resende, where I learned how to expose and consume APIs within an OutSystems environment. The project is a fictitious game shop e-commerce platform, utilizing game data provided by an external API. This project was completed in under 10 days, and it was my first experience working with APIs and developing mobile applications in OutSystems.

## Functionalities

The project is divided into two main parts:

1.  **Mobile Application for the Customer:**

    *   **Registration:** Allows new customers to register via a form, with data persisted in both the application and the store's database via the API.
    *   **Intuitive Navigation:** All screens feature top and bottom navigation shortcuts for ease of use.
    *   **Home Screen:** Showcases a search field and four curated game selections, displayed as cards in a carousel.
    *   **Search:** Enables filtering of products by minimum and maximum price, as well as by game genre or platform.
    *   **Game Details:** Provides detailed information about each game, including price, description, cover image, developer, and release date.
    *   **Shopping Cart:** Allows users to add games to their cart, remove items, and complete purchases, sending orders to the store.
    *   **Orders:** Displays a list of all customer orders, with the ability to view details of specific orders, including purchased games and order status.

2.  **Web Application for the Seller:**

    *   **Game Viewing and Management:** Allows viewing of all store products, modification of data, and addition of new games. Game addition leverages the external API to fetch game images, names, and descriptions.
    *   **Order Management:** Enables viewing of customer orders, checking order details, confirming item separation, updating order status, and canceling orders.
    *   **User Administration:** Provides a dedicated interface for managing users, including assigning and revoking access permissions to system functionalities.

## Screenshots/Images

1.  **Web Application for the Seller:**

<p align="center">
  <div style="display: flex; justify-content: center; gap: 20px; align-items: center;">
    <img src="Mobile_API_Outsystems/Pictures_Mobile_API/Capturadeecrã2025-03-02184411.png" width="500" height="300" style="object-fit: cover;" />
    <img src="Mobile_API_Outsystems/Pictures_Mobile_API/Capturadeecrã2025-03-02184556.png" width="500" height="300" style="object-fit: cover;" />
  </div>
  <br>
  <div style="display: flex; justify-content: center; gap: 20px; align-items: center;">
    <img src="Mobile_API_Outsystems/Pictures_Mobile_API/Capturadeecrã2025-03-02184650.png" width="500" height="300" style="object-fit: cover;" />
    <img src="Mobile_API_Outsystems/Pictures_Mobile_API/Capturadeecrã2025-03-02184731.png" width="500" height="300" style="object-fit: cover;" />
    <img src="Mobile_API_Outsystems/Pictures_Mobile_API/Capturadeecrã2025-03-02184819.png" width="150" height="300" style="object-fit: cover;" />
  </div>
</p>

2.  **Mobile Application for the Customer:**

<p align="center">
  <div style="display: flex; justify-content: center; gap: 100px; align-items: center;">
    <img src="Mobile_API_Outsystems/Pictures_Mobile_API/Capturadeecrã2025-03-02185104.png" width="150" height="300" style="object-fit: cover;" />
    <img src="Mobile_API_Outsystems/Pictures_Mobile_API/Capturadeecrã2025-03-02185227.png" width="150" height="300" style="object-fit: cover;" />
    <img src="Mobile_API_Outsystems/Pictures_Mobile_API/Capturadeecrã2025-03-02185404.png" width="150" height="300" style="object-fit: cover;" /> 
  </div>
  <br>
  <div style="display: flex; justify-content: center; gap: 20px; align-items: center;">
    <img src="Mobile_API_Outsystems/Pictures_Mobile_API/Capturadeecrã2025-03-02185434.png" width="150" height="300" style="object-fit: cover;" />
    <img src="Mobile_API_Outsystems/Pictures_Mobile_API/Capturadeecrã2025-03-02185659.png" width="150" height="300" style="object-fit: cover;" />
  </div>
</p>

## Architecture

The project is structured using two main modules in each application:

*   **Front-end:** Handles user interface and interaction with the back-end.
*   **Back-end:** Manages business logic, data access, and overall system functionality.

## Technologies

*   OutSystems Platform (O11)
*   External API providing game data

## Learnings

This project facilitated learning in the following areas:

*   Exposing and consuming REST APIs.
*   Developing mobile applications in OutSystems, including leveraging features like local storage and on-demand updates.
*   Utilizing mobile-specific resources, such as optimized navigation for smaller screens.
*   Developing responsive web applications for desktop.

## Next Steps

*   Enhance the user interface for improved intuitiveness and responsiveness.
*   Implement additional features, such as reporting and payment system integration.
*   Conduct security and performance testing to ensure system quality.

