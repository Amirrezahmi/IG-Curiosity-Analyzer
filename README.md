# Instagram Curiosity Analyzer

This repository contains a Python script that uses the `instagrapi` library to analyze the curiosity level of your Instagram followers based on their interaction with your stories. By calculating the percentage of followers who consistently view your stories, you can gauge their curiosity and engagement. Additionally, the script provides information about followers who are 100% curious and displays their profile information.

## Usage


To use this notebook:


  1. Open the `main.ipynb` notebook in Google Colab.
  2. Run each code cell sequentially.
  3. Modify the provided username and password variables with your Instagram credentials.
  4. Make sure to install the required libraries by running the following code cell:
      ```python
      !pip install colorama
      ```
     ```python
     !pip install instagrapi
      ```
5. Run the script by executing the code cells.

## Script Explanation

The script performs the following steps:

   1. Logs in to your Instagram account using the provided credentials.
   2. Retrieves all the stories posted by your account.
   3. Retrieves the number of viewers and their usernames and full names for each story.
   4. Calculates the curiosity percentage of each viewer by determining how many of your stories they have viewed.
   5. Displays the viewers' curiosity percentages and identifies followers who are 100% curious.
   6. Retrieves and displays profile information for the followers who are 100% curious.


## Important Note

To accurately measure curiosity, it is recommended that you post a series of 11 identical stories. This repetition ensures consistent calculation of curiosity based on the viewership across all stories.


## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1.  Fork the repository.

2. Create a new branch: git checkout -b my-new-branch.

3. Make your changes and commit them: git commit -m 'Add some feature'.

4. Push to the branch: git push origin my-new-branch.

5. Submit a pull request.

    

## License

This project is licensed under the [MIT License](https://opensource.org/license/mit/).
