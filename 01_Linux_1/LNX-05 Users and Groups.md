# Gebruikers en Groepen 

In Linux heb je zoals elke OS gebruikers, vergelijkbaar met accounts op Windows en MacOS. 
Gebruikers kunnen deel uitmaken van groepen en hebben een eigen homedirectory. 
Één gebruiker heeft volledige priveleges met de titel 'root'. De Root heeft alle admin rechten. 
Om tijdelijke root-rechten te krijgen, kun je 'sudo' typen voor een opdracht, maar dat werkt alleen als je dat mag doen.

# Key-terms

adduser = To add a new user

sudo = Allows regular users to run programs with the security privileges of the superuser or root

usermod or sudo usermod -aG = To add a user to a group (The -aG option tells the system to append the user to the specified group) 

# Opdracht

Maak een nieuwe gebruiker in uw virtuele machine.
De nieuwe gebruiker moet deel uitmaken van een beheerdersgroep die ook de gebruiker bevat die u tijdens de installatie hebt gemaakt.
De nieuwe gebruiker moet een wachtwoord hebben.
De nieuwe gebruiker moet 'sudo' kunnen gebruiken
Zoek de bestanden waarin gebruikers, wachtwoorden en groepen zijn opgeslagen. Kijk of u de gegevens van uw nieuw aangemaakte gebruiker daar kunt vinden.

# Gebruikte bronnen

How To Add User To Sudoers & Add User To Sudo Group on Ubuntu https://phoenixnap.com/kb/how-to-create-sudo-user-on-ubuntu

# Ervaren problemen

Ik vond deze oefening pittig en leerzaam. meest voorkomende probleem was dat ik te snel commands uit de online bron copy/paste en niet overzag dat ik de ene keer root user of new user was. Hierdoor heb ik veel te lang over een vrij korte opdracht.

# Resultaat

