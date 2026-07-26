# Workshop on Coding for Biochemistry and Molecular Biology Class
## BCCE -- July 26, 2026

CodeBMB Workshop
codingfor bmb@gmail.com

Concept of notebook-based learning: 
- Colab allows code to be provided -- turnkey materials and community
- Students learng some coding while performing BMB tasks
- Cloud-based coding runs in any browser, so no installation required

The TPACK Framework - Mishra & Koehler (2006)
- Knowledge of technology - Colab, GitHub, Python, in addition to BLAST, visualization tools.., etc....
- But let's make sure it is deepening student learning

### GitHub
GitHub is an online system
Can search for a public repository
And then Fork to copy into my repo
We will not auto get updates
 This branch is up to date with codeBMB/July26_BCCE:main.

### https://colab.research.google.com/
Opened notebook > GitHub > pick file
Save > Save in GitHub repo creates a link in GitHub that allows students to access Colab

    When I work in Visual Studio, I am using my own computer (or I need to join a network) and I push / pull from GitHub. Here.... Instead of VS, I use Colab to push / pull from GitHub.

When having students use the link: Have them save the file in their own Google Drive. This saves a record of everything that they do.

In Colab:
- Connect; CPU is a good standard runtime. For more complex, ML, etc, GPU - but that limits what you can use
- View resources
- CPU generally fine!!

Colab comes with many popular Python libraries pre-installed (like NumPy, Pandas, and Matplotlib — you'll meet these in the next notebook). But sometimes you need to install additional ones.

```python
# Install a package using pip
# 'emoji' is a fun library that lets you use emojis in Python
!pip install emoji --quiet # installs emoji in a different temp colab environment - when I close out colab, emoji goes away. Need to install each time. --quite: but don't show me all of the steps
# Now import and use it
import emoji
print(emoji.emojize("Python is :snake: awesome! :party_popper:"))
# Once it is installed it works for THIS notebook - not for any other notebok.```

## Some notes about Colab vs GitHub
I need to keep 


