# Anit-Forensics
A Repository to Track Anti-Forensic Techniques

This list is built based on the response of the #DFIR community and the techniques we currently cover in our Anti-Forensics course.

## Do you have any cool Anti-Forensic ideas to share? #DFIR #DigitalForensics
https://twitter.com/binaryz0ne/status/1618828773268520961

## Data, Web, and Application Level
- File Formats Manupilation: PDF, ZIP, DOCX, RAR, 7zip, etc
- Data Hiding
- Steganography
- Encryption
"Encrypt all the things"
@rwx_08, https://twitter.com/rwx_08/status/1618904019816292355
- "If you're using a web shell, disable IIS logging via appcmd"
@keydet89, https://twitter.com/keydet89/status/1618952758287286273

## Operating System and Virtualization Related
- "Timestomping Windows Registry Keys"
@inversecos, https://twitter.com/inversecos/status/1618862849572605955
- "As you're leaving the system, clear ShimCache"
- "If you're in over RDP, disable tracking (JumpLists, etc.) for the user account"
@keydet89, https://twitter.com/keydet89/status/1618952758287286273
- "bring in your badness on a VM, delete it when you're done"
@keydet89, https://twitter.com/keydet89/status/1618954586685075459
- "I had my recent case where Dharma ransomware deletes the VSS and event logs thru a script called "purgememory.ps1" Pretty much the same as what this article mentioned"
@r3nzsec, https://twitter.com/r3nzsec/status/1618862323221004289

## Logs Related
- "Editing of existing EVTX entries"
@inversecos, https://twitter.com/inversecos/status/1618862849572605955
- "You can EDIT existing entries inside EVTX files to change what the log entries say. Dont trust yo logs ;)"
@inversecos, https://twitter.com/inversecos/status/1618863346991890433
- "Disable various WEVTX logs"
@keydet89, https://twitter.com/keydet89/status/1618952758287286273
- "The Audit Log was Cleared: https://youtu.be/00EwvDKaKyQ One of my favorites"
@Cyb3rSn0rlax, https://twitter.com/Cyb3rSn0rlax/status/1619002937296179200

## File System Related
- "time stomping FN attribute of the MFT (most analysts dont know this is even possible)"
- "tampering with $J to evade timestomp detection"
@inversecos, https://twitter.com/inversecos/status/1618862849572605955
- "Depending on the system, disable USN change journal"
@keydet89, https://twitter.com/keydet89/status/1618952758287286273
- "SSD information hiding, there is a way of hiding information in SSDs so it can't be read by the firmware and OS subsequently. I worked on that when I was a Master’s student a long time ago, it had great potential at the time."
@ask_mecca, https://twitter.com/ask_mecca/status/1618886955395350528

## Time Related (Wasting the analyst time by misleading them)
- "Give the analyst something to find so they stop looking - don’t let it get to tier  2+"
@MattETurner, https://twitter.com/MattETurner/status/1618844853403799555

## Videos
Good Anti-Forensics AF, https://www.youtube.com/watch?v=A4GYhGDCRSM

## Great ideas
- "" The key thing to understand is this:
1. You don't *have* to do anti-forensics in most cases; it's likely not necessary.
2. Don't delete artifacts when you can configure the system so that they're never written.""
@Keydet89, https://twitter.com/keydet89/status/1618954586685075459


More coming...
