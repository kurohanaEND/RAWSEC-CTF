Recently I joined RAWSEC CTF and this is my team write up
For the first question Last Hope

It is quite easy once the hint is given
all you need to do is to do some aircrack on the file 

aircrack-ng RAWSECWIFI-01.cap -w /usr/share/wordlists/rockyou.txt 
![Screenshot 2024-03-07 085454](https://github.com/kurohanaEND/RAWSEC-CTF/assets/162521380/71fabda0-dc5f-4255-abe1-0f53661808ee)
![Screenshot 2024-03-07 085443](https://github.com/kurohanaEND/RAWSEC-CTF/assets/162521380/4f5bdb8f-1ca4-4916-a3ec-68b826be17a3)


For the Question which is Medellin Cartel

At first I thought you need to find some hidden file within the photo given so I try to binwalk the photo even exiftool but still nothing was found
Even after the hint was given I am pretty clueless pretty skill issue right xD. Untill one of my teammate callout the the name nelsonhernandez on IG 

Medellin Cartel:

Blacky AKA Nelson Hernandez is the only sicarios that has went to uniten IG. U should focus on that acc only. For real - If u went to other sicarios, u will get lost. Next step? Technical stuff. Dig the flag inside the IG, metadata is there.

So I tried search IG on my phone and still found nothing and just thought its some useless hint and go on. Until the final sprint when I tried to open the acc on my potato pc and miracle is birth I accidentally found the flag
![Screenshot 2024-03-06 074722](https://github.com/kurohanaEND/RAWSEC-CTF/assets/162521380/a113bef7-8b96-4b6a-9f5a-7134fcf95a12)
