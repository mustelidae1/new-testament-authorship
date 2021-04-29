## New Testament Authorship
The New Testament consists of twenty-seven distinct works drafted by a variety of authors. Of these authors, none is more important than Paul. He is responsible for writing thirteen of the New Testament letters addressed to various churches within the Roman Empire in the decades following the crucifixion of Jesus. However, most biblical scholars agree that Paul did not actually write at least half of the letters traditionally attributed to him.   

This project uses machine learning to provide insight on the authorship of Pauline works in the New Testament. It currently uses logistic regression and a neural net to predict whether Greek texts were written by Paul. Further development is planned to refine the models and provide more accurate results. 

## How To Run 
The project requires the [CLTK](http://cltk.org/), sklearn and tensorflow libraries, so ensure that these are installed before you begin.

The first time you open the project, run up to the second cell to download the Tesserae Greek Corpus. You will then need to create a .env file at the top level of the project folder with a DATA_DIR value containing the filepath of the downloaded corpus. For Windows, the default download location is C:\Users\<your-user-name>\cltk_data\text\grc_text_tesserae\texts\.  

Once you have done this, the entire notebook can be run. Note that during development, some objects were saved into .pkl files. Cells which call load_obj contain commented out code which can be run to generate the associated objects. 
