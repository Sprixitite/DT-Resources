# Topic 2 · Data & Information 📊

This topic covers the differences between data, information and knowledge; the factors that affect the quality of data; methods of data validation, data verification and factors that limit them.

---

### 2.2.1 Differences Between Data, Information & Knowledge

> **Data →** Unprocessed facts and figures, ::without meaning or context::.

> **Information →** Processed data, ::given meaning & context::.

> **Knowledge** **→** ::Applying rules:: to information to ::allow decisions to be made::.

> **Q: Define data, with reference to the coloured table cell.**

> #### **EXAMPLE**

| **Department** | **Target Sales / £** | **Actual Sales / £** |
| -------------- | -------------------- | -------------------- |
| *Men*          | 15 000               | 12 341               |
| *Woman*        | 20 000               | 21 304               |
| *Children*     | 10 000               | 10 312               |

> A: Data is unprocessed facts & figures, without meaning or context. In this case, the figure 12 341 is the data as it is unknown and has no context or meaning.

> **Q: Define information, with reference to the coloured table cell.**

> A: Information is processed data, that has been given meaning or context. In this case, the figure 12 341 has now been given meaning, as we can clearly see that it is the amount of money gained in sales from the mens section within the store.

> **Q: Define knowledge, with reference to the coloured table cell.**

> A: Knowledge is applying rules to information to allow decisions to be made. In this instance, the store may decide to shrink and shut down the mens department due to the lack of earnings.

### 2.2.2 Quality Of Information

When thinking about the factors that affect the quality of information, think **::UCARP::**!

![Picture 1.png](https://secure-res.craft.do/v2/RUsFwTaXVnYBJYETYEWeNfWsQ4Kze7DuqdeKiJmp7CdpHSCnM9E1LP6dqmif1osYu78ohvjLTuHtRzCRYk5gr7Nc9GxqXZNBqSc9uxExvuY2nvL1h5xKA3FfciVfZgQ4cbzdxS6VcUHw5apTamYAszvkYH68MFpvqje9fscFfbTCamW9TaBaRQL92TpFF12wBv1ZGBo7TA7X62ddRPNZHxjiS54AVjDfqjdpJXa3WzYgdCQ76KRZehdAHwuaeAb6JbGwsh/Picture%201.jpg)

> **Up-to-date →** If information is out of date then it can reduce the quality of information; for example, if a school doesn't update student address records for 5 years, some students wont get their report.

> **Completeness →** If information is incomplete or missing, it can reduce the quality of information; for example, if a workplace doesn't have an workers’s bank account on file, the worker wont receive the money from their paycheque.

> **Accuracy →** The requirements for accuracy of information differ between use cases, where bank statements must be accurate the the penny, weather forecasts can be given to the nearest degree.

> **Relevance →** Having information that is not relevant can be a disadvantage as it adds volume to the information, which can make it harder and make it take longer to find relevant details.

> **Presentation →** If information is not presented in a way that is easily readable and easy to understand, it loses its value as a source of data.

### 2.2.3 Data Validation

Whenever data is manually copied or **::tped::**, there is a change that **::mistakas::** will be made. The person who is doing the copying may misread the **::orignial::** data and enter it incorrectly. **::This is called a transcription error::**.

   There are three types of transcription errors ⬇

   - **::Omission Errors:: →** This is when information is left out.
   - **::Substitution Errors:: →**  This is when information is complete but incorrect.
   - **::Transposition Errors:: →** This is when information is correct, but mixed up or reversed.

**::Data validation is a check performed by a computer on data::** as it is enters its system at the input stage of processing. It’s purpose is to flag and prevent data that does not conform to certain rules.

It can’t validate that any of the data is correct or what the user intended, but it does allow the computer **::to ensure that the data is *sensible, reasonable, within acceptable boundaries and complete*::**.

   There are a multitude of methods for data validation ⬇

   - **Range Check →** Data is compared against an upper and/or lower boundary. If value is outside the boundaries then the inputted data is considered invalid.
   - **Type Check →** Data is checked that it is of a particular data type. If the data is not the specified type, it will be considered invalid and not be processed.
   - **Length Check →** Data is compared that it contains a certain amount of characters. If the data does not meet the length requirements, it will be deemed invalid.
   - **Format Check →** Data is checked against a mask/pattern to determine its validity. If the data does not conform to the format, it will be considered unfit for processing.
   - **Presence Check →** Data is checked that it is present, if data is missing then the computer will flag this issue up and attempt to get a user to correct it.
   - **Check Digit →** This involves using an extra digit which is added to the end of a numeric value, if the final digit does not equal the result of the checking algorithm, it is invalid.
   - **Lookup Check →** Data is compared against a stored list of values, if the inputted data does not match any of the values, it is deemed invalid.
   - **Batch Totals →** Typically refers to the total value of one or more fields in a batch of data. These are calculated in advance, normally manually, then compared with the total calculated by the computer. If the batch total calculated has meaning then it is known as a control total, otherwise it is known as a hash total.

### 2.2.4 Data Verification

**::Data Verification is used to confirm the integrity of data entered into a system.::** It ensures it is consistent and has not been corrupted. Verification checks that data which has been entered/input **::is as intended and matched the source data.::**

   There are a multitude of methods for data verification ⬇

   - **Double Entry →** Entering the data twice into the computer system and the computer will check both copies to ensure there are no differences. Any differences will be flagged.
   - **Proof Reading →** Checking over data entered into the computer system to ensure that it perfectly matches the source of the data. If the user thinks it checks out, they confirm it.

### 2.2.5 Limits Of Verification

Data validation and verification cannot guarantee that all data entered will be correct and error free, no matter how advanced the computer systems, they will also be susceptible to human error.

