# Encrypted Node Communication
Ce projet est une démonstration de communication sécurisée entre deux nœuds en utilisant la cryptographie asymétrique pour l'échange de clés et la cryptographie symétrique pour l'échange de messages.

# Description
Ce code Python met en œuvre un serveur PKI (Public Key Infrastructure) qui génère des clés publiques et privées pour deux nœuds et signe leurs certificats. Les nœuds peuvent ensuite échanger des messages chiffrés en utilisant leurs clés symétriques partagées. Les messages sont chiffrés à l'aide de l'algorithme AES et l'échange de clés est effectué à l'aide de RSA.

Les nœuds utilisent le chiffrement asymétrique pour échanger leurs clés symétriques. Ils utilisent ensuite le chiffrement symétrique pour chiffrer et déchiffrer les messages qu'ils s'échangent.

# Installation
Clonez le répertoire :
git clone https://github.com/[votre-nom-utilisateur]/node-communication.git
Naviguez vers le répertoire :
cd node-communication
Exécutez le script Python :
python3 main.py
# Utilisation
Ce code peut être utilisé comme base pour une communication sécurisée entre deux serveurs dans une architecture de réseau distribué. Les messages sont cryptés de bout en bout, ce qui permet de garantir la confidentialité des communications.

# Dépendances
Ce code nécessite les modules Python suivants :

-os
-threading
-cryptography
-random
-string
-socket
-queue
-select
-pickle
-datetime

Vous pouvez les installer en utilisant pip :
pip install cryptography

# Auteurs
MOUAICI Mohand

# Contributions
Les contributions sont les bienvenues ! Pour proposer des modifications, veuillez ouvrir une issue ou une pull request.

# Contact
Si vous avez des questions, n'hésitez pas à me contacter à mohand.mouaici@etudiant.univ-reims.fr.

# Remerciements
Je tiens à remercier toutes les personnes qui ont contribué à ce projet.
