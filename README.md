# form-for-parking-violation

Formulário para submissão de queixa de estacionamento ilegal junto de autoridade policial, ao abrigo do n.º 5 do art.º 170.º do Código da Estrada.

* O formulário em HTML pode ser visto <a href="http://jfolpf.pt/passeio_livre/form/index.html">aqui</a>.
* A APP para Android está <a href="https://play.google.com/store/apps/details?id=com.form.parking.violation">aqui</a>.

O código está desenhado em Javascript para ser corrido num smartphone. Para tal faz uso da API <a href="https://cordova.apache.org/">Apache Cordova</a>.

## Opções

 * debug=1, ativa o modo de debug do formulário; debug=false desativa
 * images_support=1, ativa a submissão de imagens no formulário
 * map_reverse_location=1, ativa a geolocalização, mapa e reverse location
 * enable_user_cookie=1, ativa a memorização dos dados do utilizador numa cookie no browser

Exemplo:
 
 * http://jfolpf.pt/passeio_livre/form/index.html?debug=1&images_support=1&map_reverse_location=1&enable_user_cookie=1 
 * http://jfolpf.pt/passeio_livre/form/index.html?debug=false&images_support=1

APIs Utilizadas:

 * Google Maps - https://maps.googleapis.com/maps/api
 * OpenStreetMap - https://nominatim.openstreetmap.org/reverse

## Contribuição são muito bem-vindas
 
 * respeite a estrutura dos ficheiros
 * comente sempre o código (preferencialmente em Inglês), tal ajuda os outros a compreender as suas contribuiçes
 * para identações, use sempre 4 espaços (não use 2 espaços, nem tabulaçes, ou seja TAB)

## Licença

GNU GPLv3<br>
http://www.gnu.org/licenses/gpl-3.0.en.html <br>
http://choosealicense.com/licenses/gpl-3.0/
