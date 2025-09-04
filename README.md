**🖼️ Image Compression with K-Means**



This project shows how we can compress an image using K-Means clustering. The main idea is simple — instead of keeping every tiny color detail, we reduce the image to just K main colors. This way, the image still looks good, but it takes up less space.





**🔍 What happens in this project?**



1. We load an image.



2\. Every pixel (with its Red, Green, Blue values) is treated like data.



3\. Using K-Means clustering, pixels are grouped into K clusters (each cluster = a representative color).



4\. We replace every pixel with its closest cluster color.



5\. Finally, we display both the original image and the compressed version side by side.



6\. The compressed image is saved in multiple formats (like PNG, JPEG, BMP, WEBP).





**🛠 Tools \& Libraries**



* Python 3



* NumPy → handles pixel data



* scikit-learn → does the K-Means clustering



* Matplotlib → used to show the images



* scikit-image → loads the input image



* Pillow (PIL) → saves the output in different formats





📂 Project Structure



Image\_Compression/

│── Image Compression with K-Means.ipynb       # Main script (the code above)

│── lion.jpg       # Input image (replace with your own)

│── outputs\_k\_means/             # Folder where compressed images are saved

│── README.md            # Project documentation

│── requirements.txt     # Dependencies





🚀 Usage



1\. Clone the repository



&nbsp;	git clone https://github.com/your-username/Image\_Compression\_KMeans.git

&nbsp;	cd Image\_Compression\_KMeans



2\. Install dependencies



&nbsp;	pip install -r requirements.txt



3\. Run the script

&nbsp;	jupyter lab "Image Compression with K-Means.ipynb"



4\. Output



&nbsp;	Displays Original vs Compressed image side by side.



&nbsp;	Saves compressed images inside the outputs\_k\_means/ folder in multiple formats.





⚙️ Configuration



Change the number of colors (k) in the script:

&nbsp;	k = 16  # number of colors to keep



Modify output formats by editing the list: 	

&nbsp;	formats = \["PNG", "JPEG", "BMP", "WEBP"]





📌 Future Improvements



* Support for batch image compression



* Support for grayscale images



* CLI or Web interface to choose k and formats







