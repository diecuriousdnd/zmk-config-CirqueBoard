# zmk-config-Cirque40
ZMK with Cirque, Emgram (mostly) layout with mouse keys for clicks, no RGB

note: I'm using keycodes like N1 instead of KP_N1 so I can get the shifted characters
LMB, RMB = Left Mouse Button, Right Mouse Button
T/L1 = TAB when tapped, Layer 1 when held = "&lt 1 TAB" I think?
S/L2 = SPACE when tapped, Layer 2 when held = "&lt 2 SPACE" I think?
ps = LWIN + PSCRN = "LG(PSCRN)" I think? 

to do: add DEL

# Layer 0

           B   Y   O    U                 L    D   W   V
    LSHFT  C   I   E    A                 H    T   S   N   BSPC
    LCTRL  G   X   J    K                 R    M   F   P   Q
                  RMB  LMB  T/L1  S/L2  ENTER  Z

# Layer 1

           PG_UP HOME  UP    END              N7    N8   N9   PLUS
    trans  PG_DN LEFT  DOWN  RIGHT            N4    N5   N6   MINUS  trans
    trans  none  none  none  none             N1    N2   N3   FSLH   ASTRK
                       trans trans [T/L1] N0  DOT   EQUAL

# Layer 2

                  none none SEMI  DQT             QMARK  COMMA none  BT_CLR
    &soft_off     none none COLON APOS            DOT    LPAR  RPAR  BT_SEL 0 studio_unlock
    &out OUT_TOG  none LT   GT    BSLH            EXCL   LBKT  RBKT  BT_SEL 1 bootloader
                            ps    DEL  ESC [S/L2] trans  trans
