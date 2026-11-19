# Navegação Mar e Pesca ⚓🌊

**Navegação Mar e Pesca** é uma aplicação móvel avançada para Android, desenvolvida em **Kotlin** e **Jetpack Compose**, desenhada especificamente para pescadores profissionais, navegadores de recreio e profissionais do mar em Portugal. Aplicação informativa e de ajuda, nao substitui ferramentas oficias obrigatorias.

A aplicação combina cartografia online de alta precisão com modos offline robustos, assistentes de navegação em tempo real, partilha comunitária de pontos e ferramentas de segurança vitais.

---

## 🚀 Funcionalidades Principais

### 🗺️ Cartografia & Modos de Mapa
* **Mapas Online & Offline:** Suporte para Google Maps no modo online e modo minimalista offline (com polígonos de costa pré-carregados) para garantir navegação mesmo sem sinal de internet.
* **Camada Náutica (OpenSeaMap):** Sobreposição de símbolos de balizagem, faróis e ayudas à navegação.
* **Modos de Visualização:** Alternância rápida entre mapa normal e topográfico, com rotação orientada por bússola.

### 🌐 Comunidade & Partilha de Pontos (Firebase)
* **Partilha na Comunidade:** Permite partilhar pontos de pesca, rampas ou perigos diretamente com a comunidade online via Firebase Firestore.
* **Sistema de Moderação por Denúncias:** Os utilizadores podem reportar pontos indevidos ou *spam*. A partir de **3 denúncias** de dispositivos diferentes, o ponto é apagado automaticamente da base de dados e do mapa.
* **Sincronização Comunitária:** Descarregamento e sincronização em tempo real de novos pontos partilhados por outros navegadores, com prevenção inteligente de duplicados.

### 🧭 Computador de Bordo & Painéis de Navegação
* **Ecrã de Navegação:** Velocidade em nós (`kt`), rumo (`COG`), rumo magnético da embarcação (`HDG`), distância e rumo até ao alvo.
* **Meteorologia & Oceanografia:** Consulta detalhada de Previsão do Tempo, Estado do Mar, Marés e Correntes para a posição atual.
* **Registo de Trilho (Track History):** Gravação e visualização do percurso efetuado no mar, com opção de limpeza de trilho.
* **Regresso Seguro:** Cálculo e rota direta para o ponto de saída guardado ("Guardar Saída").

### 🚨 Segurança & Alertas
* **Alarme de Fundeio:** Monitorização contínua da posição do barco em relação ao ferro lançado, disparando alertas visuais e vibração intensa caso a embarcação derive além do raio configurável (ex: 75 metros).
* **Zonas Sensíveis & Reservas:** Alertas e limites visuais para áreas de proteção (ex: Arrábida, Berlengas) e canais de navegação (Tejo, Sado).
* **Checklist de Pré-Partida:** Lista de verificação essencial de segurança antes de largar ferro.

### 💾 Backup & Gestão de Dados
* **Backup e Restauro:** Exportação e importação do estado completo da aplicação.
* **Suporte GPX:** Importação e exportação de ficheiros GPX para utilização noutros softwares náuticos (OpenCPN, Google Earth, Garmin, etc.).

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** [Kotlin](https://kotlinlang.org/)
* **UI Toolkit:** [Jetpack Compose](https://developer.android.com/jetpack/compose) & Material 3
* **Base de Dados Online:** [Firebase Firestore](https://firebase.google.com/)
* **Mapas:** Google Maps Compose & [osmdroid](https://github.com/osmdroid/osmdroid)
* **Localização:** Fused Location Provider API

