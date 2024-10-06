# 📘 Lesson 1: Memory & Data Types

Welcome to the first lesson of the **Data Structures Course**, where we begin by understanding how data is stored in memory and the different data types handled by computers.

## 🧠 Memory Storage Units

Computers use **memory storage units** to store data. The most basic unit of memory is the **bit**, which can have a value of either 0 or 1. These bits are grouped together into **bytes** (1 byte = 8 bits), which form the building blocks for storing more complex data types like numbers, text, images, and sounds.

---

## 📊 Data Types: How They Are Stored in Memory

### 1. **Numbers**
Numbers are represented in binary (0s and 1s) inside a computer. Based on the type of number, different formats are used:

- **Integers**: Stored using fixed-length binary codes.
- **Floating-point numbers**: Use formats like **IEEE 754**, where the number is split into three parts: sign, exponent, and mantissa.

### 2. **Text & Characters**
Text in computers is stored as sequences of characters, with each character mapped to a numeric code.

- **ASCII**: A 7- or 8-bit encoding system that represents English characters, digits, and symbols.
- **Unicode**: A global standard for encoding characters from different languages and symbols. It can be stored in formats like **UTF-8** or **UTF-16**, which use 1–4 bytes per character.

### 3. **Images & Videos**
- **Images**: Composed of **pixels** that store color values (e.g., in **RGB** format, where each channel is stored as an 8-bit binary number).
- **Videos**: Consist of sequences of images (called **frames**), stored and displayed rapidly. Compression algorithms (e.g., **MPEG**, **H.264**) are used to reduce file size by storing only differences between consecutive frames.

### 4. **Sounds**
Sound data is stored digitally through **sampling** and **quantization** of analog audio waves:

- **Sampling**: The audio signal is measured at regular intervals (sampling rate).
- **Quantization**: Each sample is given a numeric value (bit depth). Common audio formats include **WAV** (uncompressed), **MP3** (compressed), and **FLAC** (lossless compression).

---

## 💡 Important Notes

1. **Standard Storage Unit**: A byte (8 bits) is the standard unit of memory. This convention became popular due to IBM's influence in early computer design.
   
2. **Fixed Size of Arrays**: Once an array's size is defined in memory, it cannot be changed. Any attempt to expand it results in creating a new array with the old and new values, as the memory for the array is pre-allocated.

3. **Dynamic Arrays**: Although dynamic arrays exist in higher-level programming languages, under the hood, they work by creating new arrays and copying data from the old ones to accommodate changes in size.


