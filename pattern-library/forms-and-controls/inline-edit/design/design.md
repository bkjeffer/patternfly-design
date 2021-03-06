# In-line Edit

## In-line Create and Edit
![Image of list with newly created row.](img/List_Edit_01.png)

1. **Create:** This action adds a row at the top of the list, in edit mode. All fields in the new row are editable. Default values for all fields are recommended.
2. **Save and Cancel:** These buttons are available on the right end of the row. If user selects Save (check) without entering values for all fields an error is displayed. If user selects Cancel the new row is deleted.

## In-line Edit
![Image of list with edit action.](img/List_Edit_02.png)

1. **Row Selection:** Only one row can be edited at a time. Edit puts an entire row into edit mode. The row in edit mode should be visually distinct from surrounding rows. The first editable field should be in focus with an option to tab through all remaining editable fields with keyboard navigation.
2. **Editable Fields:**  These are fields in the selected row that should change from read only into an editable state such as a text field or combobox.  
3. **Non-editable Fields:** These are fields in the selected row that should not change in appearance.
4. **Save and Cancel:** These buttons are available on the right end of the row. The check mark (Save) and X (Cancel) should replace the kebab in the editable row. Save is disabled until a change is made.
5. **Edit:** This action puts the row into an editable state. This action may be accessed through a button, an icon, or the kebab menu.
6. **Click Away:** When a new or existing row is in edit mode and changes have not been made, clicking away should act as a cancel action, exiting edit mode without confirmation. If changes have been made to the editable row, a dialog should appear to ask the user if changes should be saved before exiting edit mode.


## In-line Edit in an Expanded List View
![Image of list with expanded row and edit action.](img/List_Edit_03.png)

1. **Row Expansion:** If expansion behavior is supported, when a row is in edit mode, it should automatically expand. Editable fields that are not visible in the standard list can be edited in the expanded region. The X (close control) for the expanded region should be hidden; the expanded region cannot be collapsed in edit mode. The row should be returned back to the collapsed state once the user saves or cancels out of edit mode.
2. **Multi-Select:** Only one row can be edited at a time. If multi-select behavior is supported, and multiple rows are selected the row selections should persist when a single row is in edit mode but the associated actions should be disabled and the blue background highlighting of the selected rows should disappear. Upon exit of edit mode the row selections remain and the global actions are enabled. Upon exit of edit mode the row selections remain and the global actions are enabled.
3. **Edit:** This action may be accessed through a button, an icon, or the kebab menu and puts the row into an editable state.


## In-line Edit in a Table View
![Image of standard list view showing Edit action.](img/Table_01.png)

1. **Row Selection:** Only one row can be edited at a time. Edit puts an entire row into edit mode. The row in edit mode should be visually distinct from surrounding rows.
2. **Save and Cancel:** 
  * These buttons are usually displayed in a tab under the bottom right corner of the row.
  * The check mark should be used for save and the X for cancel. Save is disabled until a change is made.
  * When the editable row is the last one in the table, these buttons are displayed in a tab above the row.

![Image of standard list view showing Edit action.](img/Table_02.png)
