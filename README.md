# handwritten-text-extraction

## Overview

This project focuses on extracting handwritten text from various document formats (e.g., PDFs, images) and saving the extracted text into a Word document. The extracted text preserves the original formatting and alignment of the input document.

## Project Structure

- data/: Contains the input documents in various formats.
- scripts/: Python scripts for preprocessing, training, and inference.
- results/: Stores output documents with extracted text.
- models/: Contains trained model files and configurations.
- logs/: Logs generated during model training and inference.

## Installation

1. Download all the Zip Folders and arrange it in given below order then unzip all the folders:

-  data :
-  logs :
-  models : model safetensors will come inside the models folder 
-  results :
-  scripts :


To Run On the system:

1. Download all the zip files and maintain the directory mentioned below for smoother running. 
2. The directory should look like this:
   v TEST2
	v data
	 >documents
	 >extracted_texts
	 >handwritten_texts
	 >labeled_dataset
	 >printed_texts
	 >test_documents
	 >training_data
	 dataset.csv

	v logs
	 events.out.tfevents.1720002240.VedantsMacBookAir.local.20226.0
	 events.out.tfevents.1720002383.VedantsMacBookAir.local.20368.0
	 events.out.tfevents.1720004926.VedantsMacBookAir.local.22707.0
	 .......
	 events.out.tfevents.1720005123.VedantsMacBookAir.local.23041.0

	v models
	 config.json
	 model.safetensors
	 special_tokens_map.json
	 tokenizer_config.json
	 vocab.txt

	v results
	 >runs
	 output.docx

	v scripts
	 >data_processing
	 >inference
	 >text_extraction
	 >training
	 >utils
3. Install all the requirements: mentioned in the requirement.txt file.
4. Then, everything is set by just running the inference.py, and the output can be seen.

To Run On the Google Collab:
1. The above two steps will remain the same.
2. Then upload the folder to Google Drive.
3. Next step Mounting your Google Drive to Google Collab.
4. By updating a few paths in the scripts everything is set.
5. Then running the inference.py will give the required output.


## Running the Model
1. Inference file is there can directly run by making sure the paths are correct:

   !python /content/drive/MyDrive/TEST2/scripts/inference/inference.py


