# 📸 Photo Geotagger with GPX Track Visualization

Easily geotag your JPEG images using a `.gpx` file from your GPS device or smartphone! This Streamlit app matches image timestamps with GPS coordinates and adds location data directly to the image metadata (EXIF). 

[![Download Releases](https://img.shields.io/badge/Download%20Releases-blue.svg)](https://github.com/elijahamusej/photo-gpx-geotagger/releases)

## 🤔 Why This Exists

If you've ever used Strava to record a hike and snapped photos along the way, you've probably noticed:

- Your photos get auto-placed in the wrong spot (or not at all).
- Phone GPS tags are unreliable or missing.
- Strava uses your phone’s weak signal instead of the accurate GPX trail.

This tool fixes all that.

By matching the timestamp of each photo to the nearest point on your GPX track, it accurately geotags your images, so you can:

- Re-upload them to Strava (or any platform).
- Keep a precise visual record of your journey.
- Trust the map for once. 🙂

## 🌟 Features

- Upload a `.gpx` file and multiple JPEG images.
- Automatically match each photo with the nearest GPS trackpoint.
- View photo thumbnails with timestamp and GPS data.
- Download geotagged images directly.
- User-friendly interface built with Streamlit.

## 📦 Installation

To get started, clone this repository:

```bash
git clone https://github.com/elijahamusej/photo-gpx-geotagger.git
```

Navigate to the project directory:

```bash
cd photo-gpx-geotagger
```

Install the required packages:

```bash
pip install -r requirements.txt
```

## 🚀 Usage

1. Run the Streamlit app:

```bash
streamlit run app.py
```

2. Open your web browser and go to `http://localhost:8501`.

3. Upload your `.gpx` file and select the JPEG images you want to geotag.

4. The app will process the images and display them with their matched GPS data.

5. Download the geotagged images for your records.

## 📸 How It Works

The app works by:

1. Parsing the `.gpx` file to extract GPS coordinates and timestamps.
2. Reading the timestamps from the JPEG images.
3. Matching each image to the nearest GPS point based on the timestamp.
4. Updating the EXIF data of the images with the corresponding GPS coordinates.

This ensures that your photos reflect the exact locations where they were taken.

## 📊 Visualization

The app provides a visual representation of your GPS track on a map. You can see:

- The route you took.
- The locations of your photos.
- The timestamps associated with each image.

This feature helps you to better understand your journey and relive your memories.

## 🌍 Supported Formats

- JPEG images for photos.
- GPX files for GPS data.

## 🛠️ Technologies Used

- **Python**: The main programming language for the app.
- **Streamlit**: For building the web interface.
- **Folium**: For map visualizations.
- **ExifTool**: For reading and writing EXIF data.

## 📝 Contributing

Contributions are welcome! If you have suggestions for improvements or want to add features, feel free to fork the repository and submit a pull request.

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🔗 Links

For more information and updates, check the [Releases](https://github.com/elijahamusej/photo-gpx-geotagger/releases) section. 

[![Download Releases](https://img.shields.io/badge/Download%20Releases-blue.svg)](https://github.com/elijahamusej/photo-gpx-geotagger/releases)

## 📧 Contact

For any questions or feedback, please open an issue on the GitHub repository or contact the maintainer directly.

---

Thank you for using the Photo Geotagger! We hope it enhances your photo-taking experience and helps you keep track of your adventures.