# Vault-Door-3
Opening the Java code and examining it, I determine that the `checkPassword` function is the main thing which needs to be worked on \
The `checkPassword` function has four loops which are jumbling up the input and comparing it with the String `jU5t_a_sna_3lpm12g94c_u_4_m7ra41` \
So to get the buffer I place a print statement after all the loops which gives me the String `jU5t_a_s1mpl3_an4gr4m_4_u_c79a21` \
And wrapping it in flag format and submitting as password grants the access. \
Flag-`picoCTF{jU5t_a_s1mpl3_an4gr4m_4_u_c79a21}`
