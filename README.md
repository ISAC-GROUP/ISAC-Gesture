# IPMC-Group Acoustic-based gesture dataset

The dataset contains a series of gesture data perceived by sound waves for gesture recognition and related research.



## 📚Content

- **Gesture type:** digits(0-9, 10 kinds), capital letters(A-Z, 26 kinds), self-defined gestures(8 kinds).

- **Number of spectrograms:** 86,752.

- **Collecting device:** mainly Samsung Galaxy Tab S2; very few are Oppo watch and Xiaomi phone.

- The specific details include orientation, environment, posture and distance. If further clarification is needed, please feel free to contact the author.

- **Example:**

  Letter"A", Samsung Tab, 0°, lab environment, in-hand:    [p1-sss-0-1-lab-hand-18.png] ![p1-sss-0-1-lab-hand-18](p1-sss-0-1-lab-hand-18.png)

  Digit"0", Oppo watch, 0°, lab environment, on-table:   [p11-watch-0-1-lab-none-17.png] ![p11-watch-0-1-lab-none-17](p11-watch-0-1-lab-none-17.png)



## ⚙️File Structure

```bash
- /
  ├── /digits
  │   ├── /0
  │   │   ├── p1-sss-0-1-lab-hand-1.png
  │   │   ├── p11-watch-0-1-lab-none-2.png
  │   │   └── ...
  │   ├── /1
  │   │   ├── ...
  │   ├── /2
  │   │   └── ...
  │   └── ...
  ├── /extension gestures
  │   ├── /gesture0
  │   │   ├── p2-sss-0-1-lab-none-new-46.png
  │   │   ├── p3-sss-0-1-lab-none-new-14.png
  │   │   └── ...
  │   ├── /gesture1
  │   │   ├── ...
  │   │   └── ...
  │   └── ...
  └── /letters
      ├── /A
      │   ├── p1-sss-0-1-lab-hand-1.png
      │   ├── p1-sss-0-1-lab-hand-2.png
      │   └── ...
      ├── /B
      │   └── ...
      └── ...

```





## ✔️Usage

1. **Download**: Clone or download the dataset locally.

```bash
git clone https://github.com/ISAC-GROUP/ISAC-Gesture.git
```

2. **Data format:** Data sets are stored as image files in their respective category folders.

```bash
p11    -    watch    -    0    -    1    -    lab    -    none    -    20     .png
 │            │           │         │          │            │           │      │              
user       device    orientation distance  environment   posture      count  format
     
```



3. **Citation:** If you have used this dataset in your research, please refer to this dataset.



## 🔗Citation

**If you have used this dataset, please cite the following information:**

> https://github.com/ISAC-GROUP/ISAC-Gesture



## 😀Contact information

**If you have any questions or feedback, please feel free to contact us:**

- Author：[Yongpan Zou(邹永攀), Yunshu Wang(王云舒), Yanbo He(何彦博)]
- E-mail: [yongpan@szu.edu.cn; wangyunshu2018@email.szu.edu.cn; yanboheszu@gmail.com]
- Address: College of Computer Science and Software Engineering, Shenzhen University, 3688 Nanhai Ave, Shenzhen, Guangdong, China, 518060.

Thank you for using our dataset!

