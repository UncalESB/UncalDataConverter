### XML to JSON Converter (dengan Structure):
## dari
```
<?xml version=1.0 encoding=UTF-8 standalone=no?>
<Root>
	<Nomer>QIS/MNT/2021/00716</Nomer>
	<Nama>Mohamad Jaelani</Nama>
	<Tipe>Ting</Tipe>
	<Pendor>
		<Kode>29578</Kode>
	</Pendor>
</Root>
```
### dengan structure
```
<?xml version="1.0" encoding="UTF-8"?>
<xsd:schema xmlns:xsd="http://www.w3.org/2001/XMLSchema">
	<xsd:element minOccurs="0" name="Root">
		<xsd:complexType>
			<xsd:sequence>
				<xsd:element minOccurs="0" name="Nomer" type="xsd:string"/>
				<xsd:element minOccurs="0" name="Nama" type="xsd:string"/>
				<xsd:element minOccurs="0" name="Tipe" type="xsd:string"/>
				<xsd:element maxOccurs="unbounded" minOccurs="0" name="Pendor">
					<xsd:complexType>
						<xsd:sequence>
							<xsd:element minOccurs="0" name="Kode" type="xsd:string"/>
						</xsd:sequence>
					</xsd:complexType>
				</xsd:element>
			</xsd:sequence>
		</xsd:complexType>
	</xsd:element>
</xsd:schema>
```
### Menjadi
```
{
	"Nama": "Mohamad Jaelani",
	"Nomer": "QIS/MNT/2021/00716",
	"Pendor": [
		{
			"Kode": "29578"
		}
	],
	"Tipe": "Ting"
}
```
### JSON to XML Converter (dengan Structure):
## dari
```
{
	"Nama": "Mohamad Jaelani",
	"Nomer": "QIS/MNT/2021/00716",
	"Pendor": [
		{
			"Kode": "29578"
		}
	],
	"Tipe": "Ting"
}
```
## dengan/tanpa Structure (Structure sama dengan atas) Menjadi
```
<?xml version="1.0" encoding="UTF-8" standalone="no"?>
<Root>
	<Nama>Mohamad Jaelani</Nama>
	<Nomer>QIS/MNT/2021/00716</Nomer>
	<Pendor>
		<Kode>29578</Kode>
	</Pendor>
	<Tipe>Ting</Tipe>
</Root>
```
## dari
```
{
	"Nama": "Mohamad Jaelani",
	"Nomer": "QIS/MNT/2021/00716",
	"Pendor": [
		{
			"Kode": "29578"
		},
		{
			"Kode": "29578"
		}
	],
	"Tipe": "Ting"
}
```
## dengan/tanpa Structure (Structure sama dengan atas) Menjadi
```
<?xml version="1.0" encoding="UTF-8" standalone="no"?>
<Root>
	<Nama>Mohamad Jaelani</Nama>
	<Nomer>QIS/MNT/2021/00716</Nomer>
	<Pendor>
		<Kode>29578</Kode>
	</Pendor>
	<Pendor>
		<Kode>29578</Kode>
	</Pendor>
	<Tipe>Ting</Tipe>
</Root>
```
