# Online Plagiarism Checker

<img height = 350 width = 900 src="https://blog.noplag.com/wp-content/uploads/2017/04/ES1.png">

- The Online Plagiarism Checker scrapes markdown text from a Jovian notebook link, conducts a Google search for matching notebook links on Jovian, Kaggle, and Github, and returns potential matches.

- The process involves three key functions: `get_markdown_list` collects and cleans markdown text, `get_matching_results` searches for matching links using Google, and `check_matching_sentences` identifies sentence matches.

- The tool helps detect plagiarism by comparing the input Jovian notebook with existing content and provides possible matching links.
