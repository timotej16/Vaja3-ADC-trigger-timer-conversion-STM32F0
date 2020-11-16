# Vaja3-ADC-trigger-timer-conversion-STM32F0

Glede na vašo razvojno ploščico in razširitveno vezje z tipkami ter potenciometri, izberite ustrezni analogni vhod. Kateri pin je to? _____PC0_____.
Glede na potenciometer na vaši ploščici izberite-obkljukajte ustrezni kanal/pin. Na zaslonu se vam mora usterzno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pina? ____ADC_IN10____.
Aktiviramo samo zeleno LED diodo na ustreznem izhodu _____PC9_____.
V Clock Configuration spremenimo APB1 Timer clock (MHz) na 16 MHz (pritisnemo ENTER). Kaj opazite? ________Nastavi frekvenco na 16 MHz________.
V razdelku TIM1, pod Counter Settings, bi radi časovniku spremenili frekvenco na 1 kHz, zato moramo frekvenco ABP1 Timer Clock preskalirati v polju Prescaler (PSC – 16 bit value). Koliko znaša ta vrednost? ________16.000________. 

KOMENTAR: Vrednost ADC pretvorb spreminjamo s potenciometrom PC0. Večjih težav z delovanjem ni bilo edino, da sprva nekaj ni delovalo zaradi kode in nastavitev, vendar sva potem tudi to težavo s podrobnim pregledom odpravila.
