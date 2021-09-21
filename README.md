# meta

## countries_ver2
### <li>countries_ver2.csv</li>
#### source : ISO, GENC, FIPS, UN, WB, MOFA, Nikkei Data Visual Team, FT-meta, Owid-meta & Covid data-set<br>
#### population:<br>
source#1: World Bank 2020<br>
source#2: United Nations World Population Prospect 2019, estimate for 2021, medium variant<br>
source#3: CIA World Factbook<br>
source#4: official stats<br>
source#5: FT meta data<br>
#### code_3digit:<br>
source#1: ISO3<br>
source#2: code_GENC(3digit)<br>
source#3: FIPS<br>
source#4: code_FT<br>
source#5: numeric_UN<br>
source#6: code_OWID<br>
source#7: misc(NK1~7, FT1,OWID_REG1)<br>
#### region:<br>
source#1: MOFA<br>
source#2: UN<br>
source#3: categorized by locations<br>
<br>
## population
### <li>population_UN.csv</li>
population in thousands<br>
source : <a href='https://population.un.org/wpp/Download/Files/1_Indicators%20(Standard)/EXCEL_FILES/1_Population/WPP2019_POP_F01_1_TOTAL_POPULATION_BOTH_SEXES.xlsx'>United Nations WPP2019</a><br>
data for 2020 : sheet_name = 'ESTIMATE' / use case = Nikkei Vdata<br>
data for 2021 : sheet_name = 'MEDIUM VARIANT' / use case = OWID covid-19 data<br>
<br>
### <li>JP_prefectures.csv</li>
population in 1<br>
source : <a href='https://www.soumu.go.jp/main_content/000762465.xlsx'>Ministry of Internal Affairs and Communications, Japan (総務省住民基本台帳、市区町村別、年齢階級別、2021年1月1日)</a><br>
all data : as of Jan 1, 2021
<br>
## country codes
### <li>iso_code.csv</li>
source : <a href='https://www.iso.org/obp/ui/#search'>ISO 3166 Country Code</a><br>
data retrieved : Sep 8, 2021
<br>
### <li>FIPS_code.csv</li>
source : <a href='https://www.geodatasource.com/resources/tutorials/international-country-code-fips-versus-iso-3166/'>International Country Code, FIPS versus ISO 3166, GeoDataSource</a><br>
data retrieved : Sep 11, 2021
### <li>MOFA_code.csv</li>
source : Ministry of Foreign Affairs, 1) <a href='https://www.ezairyu.mofa.go.jp/html/opendata/support/country.pdf'>country</a> 2) <a href='https://www.ezairyu.mofa.go.jp/html/opendata/support/area.pdf'>area</a> 3) <a href='https://www.mofa.go.jp/mofaj/area/index.html'>MOFA website->Coutry/Region </a><br>
data retrieved : Sep 16, 2021
