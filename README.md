# FantasySoccer
In this repository, I'll be studying fictional soccer squad data from the following countries, if they actually existed:
- Czechoslovakia
- Scandinavia
- Soviet Union
- Yugoslavia

Columns to work on the data cleaning/transformation:
- **Position:** Convert from the abbreviation to the actual position (e.g: GK to Goalkeeper).
def replace_pos(pos):
- **Player:** Clean additional data, by removing words such as 'RET', 'INJ' or '(captain)'. Only the player name shall be displayed in this column.
- **Date of birth:** Remove the ' (age xx)' after the actual date of birth, so this date can be converted into Python datetime object.
- **Club:** The club country name shown before the club name shall be removed. 
- **Captain?:** Based on the data in the 'Player' column, this column has got to have values such as 'captain', 'vice-captain', 'third-captain' or 'No'.



