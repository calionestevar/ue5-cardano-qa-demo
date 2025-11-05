# UE5 + Cardano QA Demo  
**Sr. QA Engineer | Garmin → Unreal Engine 5 + Cardano Automation**

> **Automated testing for a blockchain-integrated MMORPG**  
> Inspired by *Cornucopias* — mint land NFTs in-game via Cardano.

---

### Demo Video  
[Watch 2-min walkthrough](docs/demo-video.mp4) *(coming soon)*

---

### Tech Stack
- **Unreal Engine 5.4** (C++ + Blueprints)
- **Functional Testing Framework** (10+ auto tests)
- **Cardano** (Aiken + `cardano-cli-js`)
- **Cypress** (E2E wallet → mint → display)
- **GitHub Actions** (CI/CD)

---

### Test Coverage *(coming soon)*
| Type       | Count | Coverage |
|------------|-------|----------|
| Unit (FTF) | 0     | 0%       |
| E2E (Cypress) | 0  | 0%       |

---

### How to Run
```bash
# 1. Start Cardano server
cd Node-Server && npm start

# 2. Open UE5 project
UE5-Project/YourProject.uproject

# 3. Run Cypress
cd Cypress-Tests && npx cypress open
