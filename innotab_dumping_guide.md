1. Go to the SpiffyHacks website, they have the cartridge dumping tool, consult for instructions

2. After the game is dumped, make a pull request for MAME with the following info.

	"<software name="[shortname]" supported="no">
		<description>[Long Name]</description>
		<year>[year of release]</year>
		<publisher>VTech</publisher>
		<part name="cart" interface="vtech_storio_cart">
			<dataarea name="rom" size="0x8400000">
				<rom name="ROMNAME.bin" size="0x8400000" crc="[CRC]" sha1="[SHA1]" />
			</dataarea>
		</part>
	</software>"
