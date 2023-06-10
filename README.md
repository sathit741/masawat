root = tk.Tk()
frame = tk.Frame(root, width=500, height=400)
frame.pack()
# ข้อความที่ต้องการแสดง
label = tk.Label(frame, text="Hello world!")
label.pack()

# ปุ่มที่ต้องการใช้
button = tk.Button(frame, text="Click Me", command=frame.quit)
button.pack()
root.mainloop()
