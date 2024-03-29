# IG-FOLLOWBACK
Python GUI to see who doesn't follows you back on instagram

## Installation

Clone this repository using

```bash
git clone https://github.com/Gav3xe/IG-FOLLOWBACK_beta1
```

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install tkinter

```bash
pip install tk
```
Then install bs4 using

```bash
pip install bs4
```

## Usage
- Go to the [Download your information page](https://www.instagram.com/download/request/), insert your email and click "Next"

![Download_your_information](https://github.com/Gav3xe/IG-FOLLOWBACK_beta1/blob/imgs/Download_your_information.png?raw=true)   
_Within a few minutes you should receive an email containing your information_ (**_The link will only work for 4 days after submission_**)

- Unzip the _.zip_ file

- Navigate to the **_followers_and_following_** folder

- Execute FOLLOWBACK.py with

```bash
sudo python3 FOLLOWBACK.py
```

- Import **_following.html_** and **_followers_1.html_** in the respective box using drag and drop or by pressing the buttons below

- Once imported both files press the **FOLLOWBACK** button to generate the _**No_followback.html**_ file

  > It shoud be in the same working directory of the script
  
- Open the _**No_followback.html**_ file with your favorite browser and you will see the usernames of users not following you back 
  > You can press on the username to see the IG profile

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
