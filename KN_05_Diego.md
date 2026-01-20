VPC (Virtual Private Cloud)

Eine VPC ist ein logisch isoliertes, virtuelles Netzwerk in AWS. Du definierst darin den IP-Adressbereich (CIDR), und AWS stellt dir innerhalb dieser VPC Netzwerk-Bausteine bereit (Subnets, Route Tables, Internet Gateway, Security Groups usw.). Alles, was du in dieser VPC startest (z. B. EC2-Instanzen), bekommt private IPs aus diesem VPC-Bereich.

Subnet (Subnetz)

Ein Subnetz ist ein Teilbereich (ein “Ausschnitt”) des IP-Ranges der VPC. Jede EC2-Instanz liegt immer in genau einem Subnetz (und damit auch in genau einer Availability Zone). Das Subnetz bestimmt u. a., welche IPs möglich sind und über Route Tables indirekt, ob es “öffentlich” oder “privat” ist (Internet-Gateway Route vorhanden oder nicht).

Public IP vs. Private IP

Private IP: interne Adresse innerhalb der VPC. Sie wird nur im AWS-Netz geroutet (zwischen Instanzen/Subnets/VPC-Komponenten). Sie ist ideal für interne Services wie Datenbanken.

Public IP: öffentlich erreichbare Adresse im Internet. Damit eine Instanz von außen erreichbar ist, braucht sie (a) eine public IP und (b) passende Routes (z. B. Subnetz-Route zum Internet Gateway) und (c) passende Security-Group-Regeln.
