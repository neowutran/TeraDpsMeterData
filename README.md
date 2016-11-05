# TeraDpsMeterData
Data for Tera DPS meter

How to get opcode:
--------------------
GoneUp method: https://github.com/GoneUp/Tera_PacketViewer/tree/master/Opcode%20DLL

How to read the database: 
----------------------
https://github.com/gothos-folly/TeraDataTools

Decrypted Database repository:
----------------------
https://cloud.neowutran.ovh/index.php/s/oBn8azZp83tujjY

File formats:
----------------------
HotDot*.tsv:

AbnormalId	AbnormalType	HPChange	MPChange	Method	Time	Tick	Amount	Name	Itemid	ItemName	Tooltip	IconName


skills*.tsv:

SkillId	Race	Gender	Class	SkillName	Chained	SkillDetailedInfo IconName


pet-skills*.tsv:

SummonName	SkillId	SkillName


glyph*.tsv

GliphId	SkillName	SkillId	SkillIconName	GlyphName	GlyphIcon	Tooltip

There are some issues in glyph*.tsv, skill Id and icon can be wrong or even absent, especially for non-english files
