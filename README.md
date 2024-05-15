Setup Instructions

Follow these steps to set up and run the project:

1. Open Anaconda Prompt.
2. Create a new environment with Python 3.9:
   bash
   conda create --name image python==3.9
   
3. Confirm by typing y and pressing Enter.
4. Activate the newly created environment:
   bash
   conda activate image
   
5. Navigate to your project directory. Replace downloads and image-caption-generator-master with your actual file paths if different:
   bash
   cd Downloads
   cd image-caption-generator-master
   
6. Open the project folder in Visual Studio Code:
   bash
   code .
   
7. Install the required packages:
   bash
   pip install -r requirements.txt
   
8. Run the application:
   bash
   python app.py
