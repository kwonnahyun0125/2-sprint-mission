## 기본 요구사항
- [x] class 키워드를 이용해서 Product 클래스와 ElectronicProduct 클래스를 만들어 주세요.
- [x] Product 클래스는 name(상품명) description(상품 설명), price(판매 가격), tags(해시태그 배열), images(이미지 배열), favoriteCount(찜하기 수)프로퍼티를 가집니다.
- [x] Product 클래스는 favorite 메소드를 가집니다.
- [x] favorite 메소드가 호출될 경우 찜하기 수가 1 증가합니다.
- [x] ElectronicProduct 클래스는 Product를 상속하며, 추가로 manufacturer(제조사) 프로퍼티를 가집니다.

- [x] class 키워드를 이용해서 Article 클래스를 만들어 주세요.
- [x] Article 클래스는 title(제목), content(내용), writer(작성자), likeCount(좋아요 수) 프로퍼티를 가집니다. Article 클래스는 like 메소드를 가집니다.
- [x] like 메소드가 호출될 경우 좋아요 수가 1 증가합니다.

- [x] 각 클래스 마다 constructor를 작성해 주세요.

- [x] 추상화/캡슐화/상속/다형성을 고려하여 코드를 작성해 주세요.

- [x] 'https://panda-market-api-crud.vercel.app/docs' 의 Article API를 이용하여 아래 함수들을 구현해 주세요.
- [x] getArticleList() : GET 메소드를 사용해 주세요.
- [x] page, pageSize, keyword 쿼리 파라미터를 이용해 주세요.
- [x] getArticle() : GET 메소드를 사용해 주세요.
- [x] createArticle() : POST 메소드를 사용해 주세요.
- [x] request body에 title, content, image 를 포함해 주세요.
- [x] patchArticle() : PATCH 메소드를 사용해 주세요.
- [x] deleteArticle() : DELETE 메소드를 사용해 주세요.

- [x] fetch 혹은 axios를 이용해 주세요. 응답의 상태 코드가 2XX가 아닐 경우, 에러 메시지를 콘솔에 출력해 주세요.

- [x] .then() 메소드를 이용하여 비동기 처리를 해주세요.

- [x] .catch() 를 이용하여 오류 처리를 해주세요.

- [x] 'https://panda-market-api-crud.vercel.app/docs' 의 Product API를 이용하여 아래 함수들을 구현해 주세요.
- [x] getProductList() : GET 메소드를 사용해 주세요. page, pageSize, keyword 쿼리 파라미터를 이용해 주세요.
- [x] getProduct() : GET 메소드를 사용해 주세요. createProduct() : POST 메소드를 사용해 주세요.
- [x] request body에 name, description, price, tags, images 를 포함해 주세요.
- [x] patchProduct() : PATCH 메소드를 사용해 주세요.
- [x] deleteProduct() : DELETE 메소드를 사용해 주세요.

- [x] async/await 을 이용하여 비동기 처리를 해주세요.

- [x] try/catch 를 이용하여 오류 처리를 해주세요.

- [x] getProductList()를 통해서 받아온 상품 리스트를 각각 인스턴스로 만들어 products 배열에 저장해 주세요.
- [x] 해시태그에 "전자제품"이 포함되어 있는 상품들은 Product 클래스 대신 ElectronicProduct 클래스를 사용해 인스턴스를 생성해 주세요.
- [x] 나머지 상품들은 모두 Product 클래스를 사용해 인스턴스를 생성해 주세요.

- [x] 구현한 함수들을 아래와 같이 파일을 분리해 주세요. export를 활용해 주세요.
- [x] ProductService.js 파일 Product API 관련 함수들을 작성해 주세요. ArticleService.js 파일에 Article API 관련 함수들을 작성해 주세요.

- [x] 이외의 코드들은 모두 main.js 파일에 작성해 주세요. import를 활용해 주세요.
- [x] 각 함수를 실행하는 코드를 작성하고, 제대로 동작하는지 확인해 주세요.

- [x] 심화 요구사항 Article 클래스에 createdAt(생성일자) 프로퍼티를 만들어 주세요.
- [x] 새로운 객체가 생성되어 constructor가 호출될 시 createdAt에 현재 시간을 저장합니다.

## 주요 변경사항
- 
- 

## 스크린샷
![image](이미지url)

## 멘토에게
- 따뜻함과 자상함이 묻어나는 코드리뷰 부탁드리겠습니다.
- 아직 개념이나 용어에 익숙하지 않아 이런거 수정해야하는 곳 알려주셔도 제가 이해를 못 할 수 있습니다.
- 죄송하지만 최대한 초등학생한테 설명 하듯이 해주셨으면 너무 감사하겠습니다.
