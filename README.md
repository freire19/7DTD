# The Walking Dead — servidor 7 Days to Die (PC)

Pacote de mods do cliente para jogar no servidor **The Walking Dead** (mapa Deadwake 10K, zumbis DoubleG/Guppy,
armas Izayo, chefões AEC, tempestades de horda, noites escuras…). **Só PC** — console não entra (mods com DLL, EAC desligado).

## O que você precisa
- **7 Days to Die V 3.4.0** (versão normal da Steam, atualizada).
- Uns **4,5 GB** livres.

## Instalação (uma vez)
1. Na página **[Releases](../../releases/latest)** baixe os 3 arquivos:
   `TWD-Mods-parte1.zip`, `TWD-Mods-parte2.zip`, `TWD-Mods-parte3.zip`.
2. Abra a pasta do jogo: Steam → botão direito em *7 Days to Die* → *Gerenciar* → *Ver arquivos locais*.
3. Se já existir uma pasta `Mods` com outros mods, **mova esses mods para outro lugar** (pode deixar só a `0_TFP_Harmony`, que vem com o jogo).
   Se a pasta `Mods` não existir, crie.
4. **Extraia os 3 zips dentro da pasta `Mods`**. No final deve ficar assim:
   ```
   7 Days To Die/Mods/0-SCore-3.4.1.1453/
   7 Days To Die/Mods/DoubleG_Zombies_3.4/
   7 Days To Die/Mods/Fluffy Panda AH64Jimbo Deadwake 10k/
   ... (33 pastas, lista em MODS.txt)
   ```
   Atenção: cada pasta de mod tem que estar **direto** dentro de `Mods` (não `Mods/TWD-Mods-parte1/...`).

## Para jogar
1. Na Steam clique em **Jogar** e escolha **"Jogar sem EAC" / "Launch without EasyAntiCheat"**
   (ou no launcher do jogo, desmarque *Use EAC*). Com EAC ligado o jogo **ignora os mods**.
2. *Entrar em um jogo* → procure **The Walking Dead** na lista (mostre servidores sem EAC / modificados),
   ou conecte pelo IP que o dono do servidor passar, porta **26900**.
3. A primeira entrada demora (o jogo baixa o mapa de 10K do servidor).

## Problemas comuns
- **Itens com "?" ou janela de baú vazia** → mods errados/antigos ou versão do jogo diferente de 3.4.0. Apague a pasta `Mods` e extraia os zips de novo.
- **"Mods incompatíveis"/expulso ao entrar** → você abriu o jogo com EAC.
- **Jogo pesado** → em *Opções → Vídeo* use Qualidade de textura **Média**, sombras médias, reflexos de tela desligados.

## Atualizações
Quando o pacote mudar, sai um Release novo aqui. Apague as 33 pastas antigas e extraia os zips novos.

Os mods pertencem aos seus autores (Nexus Mods / 7daystodiemods.com); este pacote só junta as versões usadas no servidor.
