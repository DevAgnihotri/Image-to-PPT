# Image-to-PPT

A tool that automatically converts images to PowerPoint presentations (PPT). Upload your images and generate a PPT file with each image as a slide. Ideal for creating presentations from photo collections, scanned documents, or lecture notes.

## Features

- Upload multiple images and quickly generate a PPT file.
- Each image is placed on a separate slide.
- Simple and intuitive interface.
- Fast processing and easy download of the resulting PPT.

## Tech Stack

- **Backend:** Python (core logic, image processing, and PPT generation)
- **Frontend:** HTML (user interface)
- **Libraries:** 
  - [python-pptx](https://python-pptx.readthedocs.io/) (for creating PPT files)
  - [Flask](https://flask.palletsprojects.com/) (for web server, if applicable)
  - Other Python packages as required

## Getting Started

### 1. Fork the Repository

1. Go to the [Image-to-PPT repository](https://github.com/DevAgnihotri/Image-to-PPT).
2. Click the **Fork** button in the upper right to create your own copy under your GitHub account.

### 2. Clone Your Fork

```bash
git clone https://github.com/<your-username>/Image-to-PPT.git
cd Image-to-PPT
```

### 3. Set Up a Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

If a `requirements.txt` file is missing, install the main dependencies manually:

```bash
pip install python-pptx flask
```

### 5. Run the Application

If the project uses Flask (or another web server), run:

```bash
python app.py
```

Then open your browser and go to `http://127.0.0.1:5000` (or the address shown in your terminal).

### 6. Use the Tool

- Upload your images via the interface.
- Download the generated PPT file.

---
