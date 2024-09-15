# Pandas-Challenge
- The challenge code is found under the "PyCitySchools" folder. The file name is PyCitySchools_starter.ipynb.
- The first section of the code contains a short summary of the assignment, and the next two paragraphs are conclusions from the analysis I did on the data presented. 
- This challenge includes some of the following areas: creating dataframes, functions, working with columns, reading from csv files, loc, groupby, merging data, data cleaning, binning, mapping, etc.
- For debugging I used tools like Xpert Learning Assistant, and ChatGPT.
- when formatting with .map(), I had to replace the provided code with .apply() due to an error that was constantly showing on my code. I replaced with "per_school_summary["Total School Budget"] = per_school_summary["Total School Budget"].apply(lambda x: "${:,.2f}".format(x))per_school_summary["Per Student Budget"] = per_school_summary["Per Student Budget"].apply(lambda x: "${:,.2f}".format(x))". Source from ChatGPT.
- #Added this line of code to remore symbols due to persisting error since "labels" have symbols.school_spending_df["Per Student Budget"] = school_spending_df["Per Student Budget"].replace({'\$': '', ',': ''}, regex=True).astype(float). Source from ChatGPT.
