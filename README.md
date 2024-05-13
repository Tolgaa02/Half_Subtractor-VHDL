library IEEE;
use IEEE.STD_LOGIC_1164.ALL;

entity Half_Subtractor is
    Port ( a : in STD_LOGIC;
           b : in STD_LOGIC;
           d : out STD_LOGIC;
           c : out STD_LOGIC);
end Half_Subtractor;

architecture Behavioral of Half_Subtractor is

begin

    d <= a xor b;
    c <= not (a) and b;


end Behavioral;


![Half_Subtractor](https://github.com/Tolgaa02/Half_Subtractor-VHDL/assets/162368039/89e06a57-dd10-4775-917e-7d878f4a69ce)
