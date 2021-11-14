# Excel-Merger
A drag an drop support excel table merging program.<br/>
Just drag and match the key of left table and right table.<br/>
![demo](https://user-images.githubusercontent.com/94159290/141667414-4bf764e5-1f1b-44d3-88b9-dfe1f276d83f.gif)


### Limitations
I put the limitations in front so you can check whether it meet your requirements before you use it.

1. Supported to merge 2 tables only. (1 left, 1 right)
2. Perform simple condition only. (1 condition)

### Prerequisites
There is one external module call VerticalScrolledFrame.py which is upload together with the Excel-Merger.<br/>
You can also download the .exe zip and run it directly.

The rest of modules are come with Python.
- tkinter
- pandas
- os
- VerticalScrolledFrame

### How To Use
1. Load your left table and right table.<br/>
![open](https://user-images.githubusercontent.com/94159290/141667423-9d0d4516-551c-4dc8-bc9a-99852c24218f.gif)<br/>

3. Select the joining method. (Left, Right, Inner, Outer)<br/>
![method](https://user-images.githubusercontent.com/94159290/141667429-ff28a6b0-a3f0-496b-a4b8-ef0e62e32ff2.gif)<br/>

4. Match the key!<br/>
![join](https://user-images.githubusercontent.com/94159290/141667459-1397c1ba-f296-4340-9bd5-2c5c13b0153c.gif)<br/>

5. Right click to delete the column you don't want it in the output table.<br/>
![rightclick](https://user-images.githubusercontent.com/94159290/141667447-59ab8ad1-b28c-46d1-9cf7-128f6c1b48e0.gif)<br/>

6. Click Save to export the result to an excel file.<br/>Click Reset do it again.<br/>
![save](https://user-images.githubusercontent.com/94159290/141667472-84241180-48ea-492a-bef1-646da1bdc44b.gif)<br/>

