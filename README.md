# basic
- maven project + spring 모듈
- src/main/java/com.spring.basic: IOC방식으로 객체 생성에 대하여
- src/main/java/com.spring.basic.ex01: property와 constructor-arg를 이용한 객체 주입에 대하여
- src/main/java/com.spring.basic.ex02: property와 constructor-arg를 이용한 값 주입에 대하여
- src/main/java/com.spring.basic.ex03: scope="prototype"에 대하여
- src/main/java/com.spring.basic.ex04: 자동주입 어노테이션 @Autowired @Quailifier @Resource에 대하여
# SpringWebBasic
- servlet-context.xml, web.xml 설정
- 스프링 MVC흐름(dispatcherServlet handlerMapping, handlerAdapter, viewResolver)
- 요청받기(@RequestMapping, @GetMapping, @PostMapping)
- 요청 파라미터 받기(HttpServletRequest, @RequestParam, vo객체)
- 응답 페이지에 데이터 전달(Model객체, @ModelAttribute, ModelAndView객체)
- redirect시 데이터 전달(RedirectAttributes)
- service와 DAO객체의 구현
# SpringDBAccess
- root-context.xml 설정
- JdbcTemplate을 이용한 spring jdbc
- mybatis
# SpringWebMvcProject(회원가입/로그인 게시판 구현)
- <회원가입>
- 아이디 중복체크(@RestController, @RequstBody)
- 비동기 통신으로 회원가입(@RestController, @RequstBody)
- <로그인>
- 비동기 통신으로 로그인
- 세션(HttpServletRequest.getSession(), HttpSession)
- <로그아웃>
- session만료(session.invalidate())
- <게시판>
- 게시글 등록
- 글 상세/수정/삭제(@PathVariable)
- 페이징
- 검색(동적sql)
- 표시할 게시물의 개수 선택
- 조회수
- 새 게시물 new mark 표시
- UriComponents
