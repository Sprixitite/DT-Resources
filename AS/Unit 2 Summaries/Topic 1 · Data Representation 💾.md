# Topic 1 · Data Representation 💾

This topic covers how data is represented within computer systems and how binary is used to store our documents, photos & videos on our computers.

----

### Units of Storage

Computers use a variety of memory techniques to store data. All data is stored in a digital format using a number system called Binary, a singular **B**inary Dig**it** (BIT) can either be 1 or 0.

When bits are grouped together, typically in groups of eight, it is known as a byte. A singular character (such as a letter or digit) is typically represented by a singular byte.

The storage capacity in a computer is measured in bytes and its multiples.

#### Multiples Of Bytes

| **Storage Unit** | **Preceding Unit** | **Bytes** |
| :--------------- | :----------------: | :-------: |
| *Byte*           |                    | $1$$      |
| *Kilobyte*       | *1024 Bytes*       | $2^{10}$  |
| *Megabyte*       | *1024 Kilobytes*   | $2^{20}$  |
| *Gigabyte*       | *1024 Megabytes*   | $2^{30}$  |
| *Terrabyte*      | *1024 Gigabytes*   | $2^{40}$  |

### Number Systems

In the number system (the decimal/denary system) we use in our day to day lives, each integer number has values of units, tens, hundreds, thousands, etc. Values are written as index numbers starting from the right hand side $10^0$, $10^1$, $10^2$, etc. Then each position to the left of the decimal point indicates an increased positive power of 10.

Computers use the **Binary Numbering System**, where each value is written as a power of 2 starting from the right hand side, and can be indicated by either a **one** or a **zero**. For example, **0101 0101** is equal to **64 + 16 + 4 + 1** which sums up to be a decimal total of **85**.

*further information on conversion between binary and denary is in the table below*

#### Converting Binary ⇿ Denary

### Basic Conversion

In the decimal/denary system, numbers are counted **in powers of 10** whereas in the binary system, numbers are counted **in powers of 2**.

> #### EXAMPLE

| **Base Two Unit** | **Denary Value** | **Binary Position (1 Byte)** |
| :---------------- | ---------------- | ---------------------------- |
| $2^0$             | 1                | XXXX XXX**X**                |
| $2^1$             | 2                | XXXX XX**X**X                |
| $2^2$             | 4                | XXXX X**X**XX                |
| $2^3$             | 8                | XXXX **X**XXX                |
| $2^4$             | 16               | XXX**X** XXXX                |
| $2^5$             | 32               | XX**X**X XXXX                |
| $2^6$             | 64               | X**X**XX XXXX                |
| $2^7$             | 128              | **X**XXX XXXX                |

> **This pattern continues forever, the higher the number of bits, the more powers of 2 that are represented in the binary system.**

## Two’s Complement

**Two's Complement** is a method of **displaying negative numbers** in binary.

In order to indicate a negative number, we need to utilize a sign/bit to tell the computer that the number is negative. In order to achieve this, we use the **M**ost **S**ignificant **B**it (MSB).  When the MSB has a value of ONE, **the number has a negative value** whereas if the MSB has a value of ZERO, **the number will have a positive value**.

#### **0/-128**   ·   64   ·   32   ·   16   ·   8   ·   2   ·   **1**

**MSB** · **LSB**

#### **How To Indicate A Negative Number In Two's Complement**

**Convert your positive number into binary;**

$71$ ⇒ $0100$ $0111$

**Flip the bits;**

$0100$ $0111 $⇒ $1011$$1000$

**Add One.**

$1011$ $1000$ $+$ $1$ ⇒ $1011$ $1001$

### Rules of Binary Arithmetic

Binary numbers can be added, subtracted, multiplied and divided just like numbers used in the denary system, the card below contains all of the basics of binary arithmetic.

#### Basic Binary Arithmetic

## Addition Of Binary Numbers

$$0 + 0 = 0$$

$$1 + 0 = 1$$

$$1 + 1 = 10$$

$$1 + 1 + 1 = 11$$

### Characters

A **character set** is a set of **symbols** that may be **represented in a computer** at a particular time.

These symbols/characters can be classified as letters, digits & punctuation marks. Character sets also control **"control"** characters which are **non-printable**, and are used as a **special purposes** such as a end-of-file marker.

***Two examples of character sets are ASCII & Unicode.***

| **Character Set** | **On Course** | **Number of Bits** | **Max Number of Characters** |
| :---------------: | :-----------: | :----------------: | :--------------------------: |
| *ASCII*           | ✔️           | 7                  | 128                          |
| *Extended ASCII*  | ❌           | 8                  | 256                          |
| *Unicode*         | ✔️           | 16                 | 65,536                       |

