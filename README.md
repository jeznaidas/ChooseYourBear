# ChooseYourBear

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jeznaidas/ChooseYourBear/HEAD?urlpath=%2Fvoila%2Frender%2F02_deployment.ipynb)

This is part of fastai's [Practical Deep Learning for Coders](https://course.fast.ai/)'s Lesson 2 on building a Binder app from a Bear Detection Model.

I mainly use Google Colab to study and use their notebooks but Colab doesn't support Voila for this section. With [Paperspace Gradient](https://gradient.paperspace.com/), I used a Jupyter Notebook instance backed by a free GPU.

This is a screenshot of the Binder app.

![Sample](https://bit.ly/3cQPk3Z)

Initially, I used Binder but I encountered several failed launches and opted to try deploying it to Heroku. However, I think there were compatibility issues with some of the requirements (I didn't get any errors in the log of my last attempt but the last launch still failed) so I switched back to Binder with the help of this [forum](https://forums.fast.ai/t/deploying-your-notebook-as-an-app-under-10-minutes/70621). *If you also encounter issues, you might want to read through the thread as well.*
