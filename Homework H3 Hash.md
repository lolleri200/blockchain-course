x) I read the Karvinen 2022: Cracking Passwords with Hashcat documentation in preparation for the H3 assigment it was really interesting to learn about using hashes.

a) I started experiencing with different hashes with the command echo -n "hello asdf"|sha256sum to get different kind of hashes. I noticed that the longer the hash then it was easier to get a hash that starts with a zero.

b) I started by creating a new text file called sami.txt and edited the text file with a text content of gg2 and it resulted a hash that started with 1e2e and then I changed the text content to gg and the hash chnged to 4960.

c) I have installed Hashcat in Debian with the command sudo apt-get -y install hashid hashcat wget

d) Tried to crack the hash 21232f297a57a5a743894a0e4a801fc3, but Debian gives an error "attention no opencl hip or cuda compatible platform found".
   I did not want to give up with Hascat so I figoured out how to use Hashcat on Windows using a YouTube tutorial: https://www.youtube.com/watch?v=rRUiRz_znLQ and managed to crack the hash with the result of: 123456 -> tylerandanya

e) To protect yourself from someone craking your password using a dictionary attacks you need to start using more difficoult passwords with atleast +12 letters combined with big and small letters, numbers and special characters. One good way is to start using password managing tools if you don't want to remember long passwords.

Documentation with pictures: https://imgur.com/a/NMperVy
