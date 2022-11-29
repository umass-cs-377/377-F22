# Post

The last chapter introduced the general concept of an I/O device and showed you how the OS might interact with such a beast. In this chapter, we dive into more detail about one device in particular: the hard disk drive. These drives have been the main form of persistent data storage in computer systems for decades and much of the development of file system technology (coming soon) is predicated on their behavior. Thus, it is worth understanding the details of a disk’s operation before building the file system software that manages it. Many of these details are available in excellent papers by Ruemmler and Wilkes [RW92] and Anderson, Dykes, and Riedel [ADR03].

## Crux

CRUX: HOW TO STORE AND ACCESS DATA ON DISK

- How do modern hard-disk drives store data?
- What is the interface? 
- How is the data actually laid out and accessed? 
- How does disk scheduling improve performance?
