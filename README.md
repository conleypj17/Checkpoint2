# FastAPI-Based Deployment

### Explanation of Project Structure
:

app/: Contains the FastAPI application files.

main.py: The main FastAPI application that defines API endpoints.

model.py: Handles feature extraction using ResNet50 and interacts with the FAISS index.

utils.py: Contains utility functions for tasks such as image handling and preprocessing.

templates/: Stores HTML templates for the web interface.

static/: Holds static files like CSS and JavaScript for the web interface.

data/: Organizes image data.

raw/: Contains the original raw food images.

preprocessed/: Stores images resized to 300x300 pixels.

similar/: Directory to store similar images retrieved during searches.

faiss/: Stores FAISS index and metadata.

resnet_faiss.index: The FAISS index file created using ResNet50 features.

resnet_meta.pkl: A pickle file mapping image IDs to their file paths.

scripts/: Contains scripts for various stages of the project.

preprocess.py: Script to resize images to 300x300 pixels.

extract_features.py: Script to extract features using ResNet50.

build_index.py: Script to build and save the FAISS index.

requirements.txt: Lists all Python dependencies required for the project.

README.md: Provides an overview and instructions for the project.

.gitignore: Specifies files and directories to be ignored by Git.


### Input image
![Screenshot 2025-04-22 213646](https://github.com/user-attachments/assets/ec42170b-33f2-41dc-8460-9d4ae4c437f1)

### Sample output images
![Screenshot 2025-04-22 213707](https://github.com/user-attachments/assets/24510c07-72b3-4b15-b4cc-39fb492364b4)
![Screenshot 2025-04-22 213724](https://github.com/user-attachments/assets/fa71fa95-7c9d-4838-96ef-635f4d658515)



