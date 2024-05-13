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


