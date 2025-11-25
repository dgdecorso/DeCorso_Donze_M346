A) Hypervisor Typ 1 und Typ 2 – fertiger Text

Ein Hypervisor ist eine Software-Schicht, die es ermöglicht, mehrere virtuelle Maschinen (VMs) auf einem physischen Computer auszuführen. Jede VM verhält sich wie ein eigener Computer mit eigenem Betriebssystem, obwohl alle dieselbe Hardware teilen.


Unterschied kurz:

Typ 1: direkt auf der Hardware → eher für Server/Produktion.

Typ 2: als App auf einem Betriebssystem → eher fürs Arbeiten/Experimentieren am Desktop/Laptop.

Diesen Block kannst du fast 1:1 als Antwort für A verwenden.





B)

1. Vermutung zum Hypervisor-Typ

In unserer Gruppe verwenden wir VirtualBox auf Windows 11
Da die Software als normales Programm auf dem Betriebssystem installiert ist und nicht direkt auf der Hardware läuft, vermuten wir, dass es sich um einen Hypervisor Typ 2 (Hosted Hypervisor) handelt.


<img width="1337" height="436" alt="image" src="https://github.com/user-attachments/assets/fe394e96-d334-4575-946e-bdbf37d83b96" />

Weisen Sie Ihrer VM mehr Prozessoren zu, als Ihr Host-System logische Prozessoren hat. Starten Sie die VM und rufen Sie in der Konsole den Befehl  lscpu | grep "CPU(s)" auf.  (Screenshot für Abgabe nicht vergessen). Es ist möglich, dass Sie nicht mehr Prozessoren hinzufügen können als Ihr Host-System hat. Dann machen Sie den Screenshot der entsprechenden Fehlermeldung oder Einschränkung.
<img width="1170" height="655" alt="Screenshot 2025-11-18 103228" src="https://github.com/user-attachments/assets/5843e7e1-14f6-482c-9413-556356ff65af" />
<img width="855" height="269" alt="Screenshot 2025-11-25 103533" src="https://github.com/user-attachments/assets/2610efb1-9baa-4cea-8886-8bc7da9461e3" />


Machen Sie die gleichen Schritte wie eben mit der Ressource RAM. Der Linux Befehl zum Auslesen ist `free -h. Es ist möglich, dass Sie nicht mehr RAM hinzufügen können als Ihr Host-System hat. Dann machen Sie den Screenshot der entsprechenden Fehlermeldung oder Einschränkung.


<img width="944" height="170" alt="image" src="https://github.com/user-attachments/assets/fc64c605-8d1f-4118-a1ff-179f87f6662e" />
