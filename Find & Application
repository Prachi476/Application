from tkinter import *
from tkinter import ttk
root=Tk()
root.title("Find & Replace")
content=ttk.Frame(root,padding=(3,3,13,12))
label=ttk.Label(content,text="Find:")
entry=ttk.Entry(content,width=60)
label1=ttk.Label(content,text="Replace:")
entry1=ttk.Entry(content)
label2=ttk.Label(content,text="Direction:")

button=ttk.Button(content,text="Find")
button1=ttk.Button(content,text="Find All")
button2=ttk.Button(content,text="Replace")

onevar=BooleanVar()
twovar=BooleanVar()
threevar=BooleanVar()

onevar.set(False)
twovar.set(False)
threevar.set(False)

checkbutton=ttk.Checkbutton(content,text="Match whole word only",variable=onevar,onvalue=True)
checkbutton1=ttk.Checkbutton(content,text="Match case",variable=twovar,onvalue=True)
checkbutton2=ttk.Checkbutton(content,text="Wrap around",variable=threevar,onvalue=True)

radio=ttk.Radiobutton(content,text="Up",value=1)
radio1=ttk.Radiobutton(content,text="Down",value=2)

content.grid(row=0,column=0)
label.grid(row=0, column=0, sticky='e')
entry.grid(row=0, column=1, padx=2, pady=2, sticky='we', columnspan=9)
label1.grid(row=1, column=0, sticky='e')
entry1.grid(row=1, column=1, padx=2, pady=2, sticky='we', columnspan=9)
label2.grid(row=2,column=6,sticky='w')

button.grid(row=0,column=10,sticky='e' + 'w',padx=2,pady=2)
button1.grid(row=1,column=10,sticky='e' + 'w',padx=2)
button2.grid(row=2,column=10,padx=2)



checkbutton.grid(row=2,column=1,columnspan=4,sticky='w')
checkbutton1.grid(row=3,column=1,columnspan=4,sticky='w')
checkbutton2.grid(row=4,column=1,columnspan=4,sticky='w')

radio.grid(row=3,column=6)
radio1.grid(row=3,column=7)

root.configure(background='black')
root.mainloop()
