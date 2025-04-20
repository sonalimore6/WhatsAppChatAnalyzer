# WhatsAppChatAnalyzer
WhatsAppChatAnalyzer is a powerful tool designed to process and analyze WhatsApp chat data, helping investigators identify key patterns, sentiments, and critical conversations. When used in cases involving suicide victims, it can assist in uncovering signs of distress, identifying possible triggers, and detecting communication with relevant individuals. By leveraging sentiment analysis, keyword tracking, and behavioral patterns, this tool can provide valuable insights to support investigations and mental health assessments.

Getting Started
1. Fork this repository. Click on the  symbol at the top right corner.

2. Clone the forked repository.

git clone https://github.com/sonalimore6/WhatsAppChatAnalyzer

3. Navigate to the project directory.

cd ChatStatsPro

4. Create a new branch.

git checkout -b <your_branch_name>

5. Make changes in source code.

6. Stage your changes and commit

#Add changes to Index
git add .

#Commit to the local repo
git commit -m "<your_commit_message>"
CAUTION: Synch up your local repo with original repo (Upstream) before pushing your commits. This avoids unnecessary conflicts during the merge.

7. Push your local commits to the remote repo.

git push -u origin <your_branch_name>
Run on Local System
Install packages given in requirements.txt (packages need Python 3.11.0).
pip install -r requirements.txt
Run the below command to start your local server.
streamlit run app.py
