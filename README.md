# deeptelegram
This telegram bot uses motion supervised co-part segmentation to produce deepfake video notes directly in telegram.
Based on this repository https://github.com/albertoxamin/telegram-deep-fakes-bot that utilizes first-order motion model.
This version is based on https://github.com/AliaksandrSiarohin/motion-cosegmentation.


## How to use it

Open the python notebook with colab and follow the instructions on the notebook

## Enabled users

You can change the enabled users by simply adding your Telegram ID(not username or name, but ID) to the `enabled` array.

For example:

`enabled =[12345678,12344321]`

here we have enabled two users, `12345678` and `12344321`.


## Input type
You should send a square picture with a face (you can search directly in telegram and resize the picture with the in-app editor), and a circular video-note or a square video.

## Output type
Output can be in circular videonote format or square format. Toggle with /output

## Facial parts used
You can use only face or face with some hair. Toggle with /hair.



