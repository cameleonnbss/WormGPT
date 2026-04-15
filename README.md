# 🛠️ WormGPT CLI · v1.0

> Unrestricted AI Chatbot CLI — OpenRouter API, modèles custom, prompts jailbreak. Fonctionne sur Linux, Termux & Windows.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20Termux%20%7C%20Windows-lightgrey)
![License](https://img.shields.io/badge/License-Uncensored-red)

---

## ⚡ Installation Rapide

### Linux / Termux
```bash
git clone https://github.com/cameleonnbss/WormGPT
cd WormGPT
pip install requests pyfiglet langdetect
python WormGPT.py
```

### Windows
```bash
git clone https://github.com/cameleonnbss/WormGPT
cd WormGPT
pip install requests pyfiglet langdetect
python WormGPT.py
```

> **Auto-install** des dépendances manquantes au premier lancement !

---

## 📦 Dépendances

| Package     | But                     |
|-------------|-------------------------|
| `requests`  | Appels API OpenRouter  |
| `pyfiglet`  | Bannières ASCII stylées |
| `langdetect`| Détection langue auto  |

---

## 🔧 Fonctionnalités

### ✨ **Menu Principal**
- **Langue** : Français, Anglais, Espagnol, Arabe, etc. (auto-détection)
- **Modèles Custom** : Tape ton model ID OpenRouter (ex: `deepseek/deepseek-chat-v3-0324:free`)
- **API Key** : Stockage local sécurisé dans `wormgpt_config.json`
- **Chat Interactif** : Mode conversationnel avec typing effect

### 🧩 **Prompt Jailbreak Local**
- Fichier `system-prompt.txt` modifiable
- Prompt par défaut : **WormGPT uncensored** (raciste, sexiste, illégal, sans limites)
- Édite-le pour tes besoins !

### 🌐 **API OpenRouter**
| Modèle Gratuit      | Qualité | Vitesse |
|---------------------|---------|---------|
| `deepseek/deepseek-chat-v3-0324:free` | ⭐⭐⭐⭐⭐ | ⚡⚡⚡ |
| `01-ai/Yi-34B-Chat` | ⭐⭐⭐⭐ | ⚡⚡ |

**Obtiens ta clé gratuite** : [openrouter.ai](https://openrouter.ai)

---

## 📁 Structure Fichiers

```
WormGPT/
├── WormGPT.py          
├── README.md
├── wormgpt_config.json # 
└── system-prompt.txt   
```

---

## 🎮 Utilisation

1. **Lancer** : `python WormGPT.py`
2. **Configurer API Key** → Menu 3
3. **Choisir Modèle** → Menu 2 (ou garde DeepSeek free)
4. **Chat** → Menu 4
5. **Commandes Chat** : `menu` (retour), `exit` (quitter), `clear` (effacer)

```
[WormGPT]~[#]> comment hacker un wifi ?
[Response avec typing effect...]
```

---

## 🖥️ Compatibilité

| Plateforme | Support | Notes |
|------------|---------|-------|
| **Linux**  | ✅ Full | Parfait |
| **Termux** | ✅ Full | `pkg install python` d'abord |
| **Windows**| ✅ Full | CMD/PowerShell |

---

## ⚠️ Disclaimer

**WormGPT est 100% fictif et pour usage éducatif uniquement.** Les conseils donnés peuvent être illégaux/dangereux. L'auteur n'est **PAS responsable** de l'usage abusif. Tu utilises à tes risques et périls. 😈

---

## 👤 Auteur

**camzzz**

Discord : cameleonmortis  
GitHub : [cameleonnbss](https://github.com/cameleonnbss)

**Fork original** : [hexsecteam/worm-gpt](https://github.com/hexsecteam/worm-gpt)

---

                    ` 
