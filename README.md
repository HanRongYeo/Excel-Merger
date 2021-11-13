# Excel-Merger
A drag an drop support excel table merging program.<br/>
Just drag and match the key of left table and right table.<br/>

### Limitations
I put the limitations in front so you can check whether it meet your requirements before you use it.

1. Supported to merge 2 tables only. (1 left, 1 right)
2. Perform simple condition only. (1 condition)

### Prerequisites
There is one external module call VerticalScrolledFrame.py which is upload together with the Excel-Merger.

The rest of modules are come with Python.
- tkinter
- pandas
- os
- VerticalScrolledFrame

### How To Use
1. Load your left table and right table.
2. Select the joining method. (Left, Right, Inner, Outer)
3. Click Save to export the result to an excel file.<br/>Click Reset to clear the output preview.
