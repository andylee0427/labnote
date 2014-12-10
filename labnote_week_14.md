labnote from week 14 (last class)

==================================================

at aws.amazon.com you go to "EC2" and then click "instances"

there's a data center, hundreds of thousands of CPU they allocate data..
data center is matter of national security an underground bunker that
withstand nuclear attacks they each back each other up many of our
system, national security system is being run from these facilities the
matter of governance, and very protected, and not open to public imagine
a giant room with lots of hardware for us, mentally, it's a server when
you log in, it works like a server the only difference though is the
server is a box, and then inside, when you see, there's CPU, RAM etc, in
here, there's some part... elastic box.. these harddrive that are
service to the machine kind of cloudy

23:26) open up the terminal type: ping google.com what we're doing is
sending 64bytes to the server, and google.com is expanding to these
adddresses google.com is not just google.com, it's human-readable
address into non-readable stuff everybody getting fast response time?
26:00) remember, the general architecture remember there's ... internet
looks something like this/.. you're pinging google... the google is here
no, never min, let's say you're pinging me you're typing Dennis.com,
that request goes to some server (DNS?) DNS is like yellow pages the
request goes to DNS server, and it thinks "aha, it's the nummber.." it
gets type into that stuff and to minimize this DNS stuff, there's one
that close to us it's kind of complicated, so we'll minimize that stuff
my server is in China, it goes from US to China, and find local top
provider and lower and lower... that takes time but google, they run a
lot of Internet, they're not so low down their chain they put all over
the world

28:50) type: traceroute google.com step one, columbia.edu, that makes
sense it's some Columbia data center that's all internall, right? the
first Columbia is probably router let's go www. our packet is going all
over... these kinds of people, not household names, but they runs the
Internet server they're very much... high level we're tier 3, they're
tier 1 which means they own the wires

try sudo traceroute for PC type: traceroute yandex.ru for China's
website... type: traceroute renren.cn

they look for what's being blocked they're Cambridge, and they're
requesting pages from NYtimes and they see what's being censored what
are the actuall... twitter is blocked in many countries, sometimes it's
specific pages they try to learn the behavior, sometimes in China or...
sometimes it blocks the domain

41:18) let's go to server there's orphan server, first adopted child
let's move on to get to it find out its address use "public IP" type:
ping 54.69.168.6

use 'ssh' which is awesome the idea of session let's say we're going to
build a tunnel, A and B server in amazon and Columbia is not blocked you
request information from twitter and send it to that tunnel, then it
won't be blocked it establishes secure .. free speech comes with
responsibility it's not just an idea, but huge difference... how does
freedom manifest itself... some kind of hardware or medium? unless we
have ownership to full staff, free speech much ...

type: ssh -i "minus i" is identity, then you find paths to your keys and
use the PEM files which is your "key" ssh -i
\~/gDrive/admin/keys/ospeastkeys.pem 54.83.9.201

type: cd \~/gDrive/admin/keys ls -l

type: chmod gw-rwx ospkeypair.pem

type: chmod g-rw ospawskeys.csv

-l means "long", give me more information chmod means change
modification

after "chmod" then type "ssh" and the rest you find from aws
