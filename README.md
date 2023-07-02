# About

This repository contains the web version of a full stack house rental website. The project aims to provide a platform for users to post and search for house rental ads. Additionally, it includes an Android version, which is maintained in a separate repository.

## Key Features

- **Sign-up Authentication via Firebase Authentication**: Users can create accounts and log in securely using Firebase Authentication. This ensures that only authorized individuals can access the website's features.

- **Firebase Real-time Database for User Data**: User information collected during the sign-up process is stored in the Firebase Real-time Database. This allows for efficient and real-time retrieval and storage of user data.

- **Post Ad Page**: Registered users can post ads about house rentals using the dedicated post ad page. The page supports voice input for data entry and allows users to upload images of the rental properties. The images are saved in Firebase Storage for easy access and retrieval.

- **Web Scraping Automation**: The website includes a scraping page accessible only to the admin. The automation process runs in the background, scraping data from various house rental ad posting sites. The scraped data, including photos of flats and ad information, is saved in Firebase Storage and the real-time database.

- **Home Page with Ads Display**: The home page displays all the posted ads by users as well as the scraped ads. Users can browse through the available ads, and there is a search box that enables searching by name, price, or location. Voice search functionality is also available.

## Technologies Used

- Programming Languages: Python, JavaScript, HTML5, CSS
- Framework: Django
- Database: Firebase
- Storage: Firebase Storage

## License

This project is licensed under the GNU General Public License (GNU GPL) version 3.0. The GNU GPL is a widely used free software license that allows users to modify and distribute the software while ensuring that any derivative works are also licensed under the same terms.

Feel free to modify, distribute, and use the code in compliance with the terms and conditions of the GNU GPL. For more information, please refer to the [LICENSE](LICENSE) file in this repository.

This repository contains the web version of the full stack house rental website. For the Android version, please refer to the separate repository specifically dedicated to that platform.

Feel free to explore the code and documentation for further details on the project implementation and structure.