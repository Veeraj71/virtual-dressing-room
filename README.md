# Virtual Dressing Room

## Introduction

The Virtual Dressing Room is an innovative application designed to enhance the online shopping experience by allowing users to virtually try on accessories and clothing items in real-time. Leveraging advanced image processing techniques and web technologies, this system provides a realistic and interactive platform for users to visualize how different products would look on them without the need for physical trials.

## Features

- **Real-Time Accessory Try-On**: Users can virtually try on various accessories such as earrings, sunglasses, and tiaras, enabling them to see how these items complement their appearance.

- **Clothing Simulation**: The application offers a feature to try on different tops, providing a realistic apparel fitting experience that helps users make informed purchasing decisions.

- **Face Feature Detection**: Utilizes advanced algorithms to accurately detect facial features, ensuring that accessories align correctly with the user's face for a seamless virtual try-on experience.

## Technologies Used

- **Python**: The core programming language used for developing the application's backend functionalities.

- **OpenCV**: Employed for image processing tasks, including face detection and feature recognition, to facilitate accurate overlay of virtual accessories and clothing.

- **Flask**: A lightweight web framework that serves as the backbone of the application, handling user interactions and integrating various components seamlessly.

- **HTML, CSS, and JavaScript**: Used for designing the frontend interface, ensuring a user-friendly and responsive design that enhances the overall user experience.

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Veeraj71/virtual-dressing-room/
   ```


2. **Navigate to the Project Directory**:
   ```bash
   cd virtual-dressing-room
   ```


3. **Create a Virtual Environment**:
   ```bash
   python3 -m venv venv
   ```


4. **Activate the Virtual Environment**:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

5. **Install the Required Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```


6. **Run the Application**:
   ```bash
   python flask_app.py
   ```


7. **Access the Application**:
   Open your web browser and navigate to `http://127.0.0.1:5000/` to start using the Virtual Dressing Room.

## Usage

- **Virtual Accessory Try-On**:
  - Select the accessory category (e.g., earrings, sunglasses) from the menu.
  - Choose a specific accessory to try on.
  - The accessory will be overlaid on your live video feed, allowing you to see how it looks in real-time.

- **Virtual Clothing Try-On**:
  - Navigate to the clothing section.
  - Select the top you wish to try on.
  - The selected top will be virtually fitted onto your image, providing a realistic preview of the apparel.

## Contributing

Contributions to the Virtual Dressing Room project are welcome. If you have ideas for new features, improvements, or bug fixes, please follow these steps:

1. **Fork the Repository**: Click on the 'Fork' button at the top right corner of this page to create a copy of the repository in your GitHub account.

2. **Clone the Forked Repository**:
   ```bash
   git clone https://github.com/your-username/virtual-dressing-room
   ```


3. **Create a New Branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```


4. **Make Your Changes**: Implement your feature or fix in the codebase.

5. **Commit Your Changes**:
   ```bash
   git commit -m "Description of your changes"
   ```


6. **Push to Your Forked Repository**:
   ```bash
   git push origin feature/your-feature-name
   ```


7. **Create a Pull Request**: Go to the original repository and click on 'Pull Requests', then 'New Pull Request'. Select your branch to merge your changes.

## License

This project is licensed under the MIT License. For more details, refer to the [LICENSE](LICENSE) file in the repository.

## Acknowledgements

We extend our gratitude to the open-source community and the developers of the tools and libraries utilized in this project. Their contributions have been invaluable in making the Virtual Dressing Room a reality.

