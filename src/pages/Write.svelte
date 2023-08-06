<form id="write-form">
  <div class="image_form">
    <label for="image">이미지</label>
    <div class="image_form_input">
      <input type="file" id="image" name="image" />
    </div>
  </div>
  <div class="title_form">
    <label for="title">제목</label>
    <div class="title_form_input">
      <input type="text" id="title" name="title" placeholder="제목" />
    </div>
  </div>
  <div class="price_form">
    <label for="price">가격</label>
    <div class="price_form_input">
      <input
        type="number"
        id="price"
        name="price"
        placeholder="가격을 입력해주세요."
      />
    </div>
  </div>
  <div class="des_form">
    <label for="description">설명</label>
    <div class="des_form_input">
      <input
        type="text"
        id="description"
        name="description"
        placeholder="자세히 적어주세요."
      />
    </div>
  </div>
  <div class="place_form">
    <label for="place">장소</label>
    <div class="place_form_input">
      <input type="text" id="place" name="place" placeholder="위치 추가" />
    </div>
  </div>
  <div>
    <button type="submit" class="sub_btn">글쓰기 완료</button>
  </div>
</form>
