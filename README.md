# vis_hand_fb
This Jupyter Lab notebook aims at analysing usage data of "Visible Hand" Facebook Group.
Data is stored in "data" folder withn the working directory in form of xlsx file with general usage data stored
in "Daily numbers" sheet, wheres top posts are stored in "Top posts (last28 days)" sheet.

The individual posts are stored with number of commnts, reactions and views, however no date is attached, so
we only know that given post was posted within 28 days before the period recorded in "Daily numbers" sheet,
"Date" column.

To run the notebook, clone the repo to a virtual environment on you computer,
run
<code>
pip install -r requirements.txt
</code>

After that, you should be ready to run
<code>
jupyter lab
</code>

Follow the instructions, and open the notebook.
