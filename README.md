# Debloat Xiaomi Redmi devices

Testado com Redmi Note 10s

* Necessário ter o [adb](https://developer.android.com/tools/adb) (android-tools) instalado em sua distribuição GNU/Linux.
* Opções de desenvolvedor [HABILITADO em seu celular]
* Depuração USB [HABILITADO em seu celular]

## Instalar e Executar

```bash
git clone https://github.com/abairo/debloated_xiaomi_redmi
cd debloated_xiaomi_redmi
bash run.sh
```

### Tipos de limpeza

* Ajustes Iniciais: Otimizações (Bateria, Atividade segundo plano, etc...)
* Básica: Remove aplicativos e serviços indesejados, por favor revise a lista `basic.conf` antes de prosseguir.

### Agradecimento

Este programa foi um fork (debloat_samsung_android) feito para Windows. Foi adaptado em Shell Script para executar em distribuições Linux.

<https://github.com/invinciblevenom/debloat_samsung_android>
<https://github.com/slackjeff/debloated_Samsung>
