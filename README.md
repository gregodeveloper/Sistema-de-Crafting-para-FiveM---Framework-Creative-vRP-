# Sistema de Crafting para FiveM - Framework Creative (vRP)

Sistema de **crafting** desenvolvido para servidores **FiveM (GTA V)** utilizando a **framework Creative**.
Permite que jogadores criem itens a partir de recursos, respeitando peso, permissões e profissões configuradas no servidor.
Totalmente integrado ao sistema de inventário e notificações.

---

## 📦 Dependências

* [vRP](https://github.com/ImagicTheCat/vRP)
* notify
* inventory

---

## ⚙️ Funções utilizadas do vRP

* `vRP.Passport`
* `vRP.Inventory (table)`
* `vRP.GetWeight`
* `vRP.ConsultItem`
* `vRP.RemoveItem`
* `vRP.GenerateItem`
* `vRP.hasPermission`
* `vRP.hasJob`

---

## 🚀 Recursos

* Crafting interativo com consumo de itens.
* Verificação automática de peso antes de adicionar itens ao inventário.
* Sistema de crafting baseado em permissões e profissões.
* Feedback visual e sonoro utilizando notify.
* Fácil integração e configuração.

---

## 📂 Instalação

1. Baixe o recurso e coloque na pasta `resources` do seu servidor.
2. Adicione no seu `server.cfg`:

   ```cfg
   ensure nome-da-pasta
   ```
