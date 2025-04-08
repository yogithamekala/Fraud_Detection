This repository accompanies a [blog](https://www.blogger.com/u/2/blog/post/edit/1907108883869461564/3936590455618453693) post in which I walk through the design choices and methodology behind this project. The code here trains machine learning models to classify phishing emails using only the body text of the messages.

This project was developed as a personal exploration and is not actively maintained. The code is provided as-is, with the goal of transparency—for others to review, understand, and reproduce the workflow if they wish. While the codebase is somewhat unpolished (written with functionality in mind rather than long-term maintainability), it reflects the full end-to-end process I used.

If you come across any major issues or have questions about the implementation, feel free to open an issue or pull request—I'll do my best to respond when possible.

Datasets
This project depends on several publicly available datasets. During development, I placed all datasets in a folder located at ../datasets/. A full list of the datasets used, along with links and descriptions, can be found in the accompanying blog post.

Spam wordlist
The spam wordlist was created based on two sites: [here](https://www.activecampaign.com/blog/spam-words) and [here](https://blog.hubspot.com/blog/tabid/6307/bid/30684/The-Ultimate-List-of-Email-SPAM-Trigger-Words.aspx)
