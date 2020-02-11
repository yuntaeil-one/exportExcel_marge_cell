# exportExcel_marge_cell
dataTables 을 사용하여 화면을 구성했을때 marge되어있는 헤더를 포함하여 excel을 export 하는 방법

1. excelExport : onclick 이벤트에 사용, 공통함수로 생성 할 경우 중복코드를 없앨 수 있음.
2. js 파일 : jsp > script 부분에 추가하여 사용
  - tableExport.min.js
  - xlsx.core.min.js
  - FileSaver.min.js
