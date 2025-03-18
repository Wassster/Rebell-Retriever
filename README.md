# Rebell-Retriever
Het doel van dit project is het ontwikkelen van een geautomatiseerd systeem dat vacatures verzamelt en opslaat voor verdere verwerking. Momenteel worden vacatures handmatig toegevoegd aan de FlutterFlow-app, maar dit proces willen we automatiseren met behulp van scraping en een vector database. 

Door dit project worden vacatures automatisch verzameld en gestructureerd opgeslagen, zodat deze later efficiënt kunnen worden opgehaald en gematcht met studenten. 

## 🛠️ Installatie
1. **Clone de repository**:
   ```bash
   git clone https://github.com/jullie-repository.git
   cd scraper-project
   ```

2. **Maak een virtuele omgeving** en installeer de dependencies:
   ```bash
   pip install poetry # Alleen bij eerste installatie
   poetry install --no-root
   ```

3. **Start PostgreSQL met Docker**:
   ```bash
   docker-compose up
   ```