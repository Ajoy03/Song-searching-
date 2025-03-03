# Song-searching-
An algorithm to identify  the song alone with the artist form a given small snippet to text.
It is designed to run within the Google Colab notebook. <br>


**Here is how to run the project:**

1. **Open in Google Colab:**
     - Click on this link "Open in Colab" to open the notebook directly in Google Colab:


2. **Upload the Dataset(spotify-2023.csv) to google drive.**
3. **Mount the google drive on the colab notebook**
4. **Set the path(like /content/drive/MyDrive/Spotify/spotify-2023.csv):**
     -  try:
          df = pd.read_csv("set the path of the google drive here", encoding="latin1") # or encoding="cp1252"
        except UnicodeDecodeError:
          print("latin1 or cp1252 did not work, trying utf-8 with errors ignored")
          df = pd.read_csv("set the path of the google drive here", encoding="utf-8", errors = 'ignore') 
6.  **Execution:**
       -Then run each cell one by one.
       -At the end of the execution, it will take input as text. There you search a song or the name of a singar.
       -And if you want to quit the execution type "exit" in the input fiele.
