# Digital_Forensics

Using digital forensics to investigate a National Gallery heist using Autopsy in Kali Linux.

---

## Summary of the Case File

Tracy has been having an ongoing dialog with her brother about stealing
specific items (Stamps) from the National Gallery. Tracy will have correspondence on her work
computer, personal phone, and home computer relating to her conspiracy to have some
valuable items stolen.

## Suspects:

**Tracy:**

**works as a supervisor at the National Gallery** and is a recently divorced mother in the middle
of a child custody battle. Unfortunately, Tracy’s daughter (Terry) is in an expensive private school,
which Tracy can no longer afford on her salary.

**Joe:**

**the father of Terry** and is currently going through the divorce with Tracy. Joe is financially
well-off, and still bitter about the relationship problems.

**Pat:**

**Tracy’s brother.** He is a corrupt police officer of the D.C. Enforcers Bureau. He holds the
status of detective. He is very devoted to his sister and niece Terry

**Alex:**

**A Krasnovian supporter.** He is a foreigner
and lives outside the country presumably in a region called Krasnovia. Alex is seeking to embarrass America and damage public relations by defacing Foreign
Art, belonging to Krasnovia and currently on display in the National Gallery during the month of July. 

**Carry:**

**Somewhat criminally involved individual that shares family ties with Alex.** She is a Krasnovian supporter. Carry is both technologically savvy and an occasional social media user. 

For more details, please refer to the full [Case File](https://github.com/ldover29/Digital_Forensics/blob/main/Case%20File/The_2012_National_Gallery_Scenario.pdf)

---

The main focus of the investigation will be centered around Tracy. All logs pulled from Tracy's computer, personal phone, and home computer are found in the  ```tracy-phone-2012-07-15.final.E01``` file located in the ```/corpus``` directory in Autopsy.

Details from Tracy's phone came from an exisitng case file that was provided:

**Case name:** 2012-07-15-National-Gallery

**Case number:** 1EZ215-P

After searching through various logs, the following information was found and placed in the table below:

![Details of Tracys Phone](https://github.com/ldover29/Digital_Forensics/blob/a29c4592629ed7ef4d906d8110b8ccee513453b1/Images/Details%20of%20Tracys%20Phone.jpg)

The rest of the investigation consisted of more searching and creating custom tags of possible evidence for ease; such as mail, IPs, address book, and SMS. Through emails and text messages, I learned of Tracy's motives, her brother's involvement and all the aliases used.

Here a look at the text messages on Tracy's phone via Autopsy:

![sms1](https://github.com/ldover29/Digital_Forensics/blob/b0a2ab24afaa774513d071ae3c4b9ba8778f3a37/Images/sms1.png)
![sms2](https://github.com/ldover29/Digital_Forensics/blob/b0a2ab24afaa774513d071ae3c4b9ba8778f3a37/Images/sms2.png)

Emails to Tracy from Pat (alias: Perry):

![Emails 3](https://github.com/ldover29/Digital_Forensics/blob/5123160ba10381d86164e0247f31a3c7d706c52a/Images/Emails%203.png)
![Emails 4](https://github.com/ldover29/Digital_Forensics/blob/5123160ba10381d86164e0247f31a3c7d706c52a/Images/Emails%204.png)

To read the full email correspondence in cronological order, please refer to the [Correspondence Evidence Form](https://github.com/ldover29/Digital_Forensics/blob/main/Email%20Correspondence/Email%20Correspondence%20Evidence%20Worksheet.pdf)

---

Please see [The National Gallery - Full Case Report](https://github.com/ldover29/Digital_Forensics/blob/main/Full%20Case%20Report/National%20Gallery%20Heist%20-%20Full%20Case%20Report.pdf) to get a thorough look at the full investigation and findings.
