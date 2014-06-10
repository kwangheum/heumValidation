heumValidation
==============
Jquery plugin Validation

you can see <a href="http://kwangheum.github.io/heumValidation/validation.html">live demo</a>.


## Example

```javascript
$(document).ready(function(){
  $("form").heumValidation();
});

```
```html
<form>
  <input type="email" id="email" class="form-control" data-heum-min="2" data-heum-max="20" data-heum-null="false" data-heum-label="이메일"/>
  <input type="text" id="text" class="form-control" data-heum-min="2" data-heum-max="12" data-heum-null="false" data-heum-number="true" data-heum-label="숫자"/>
  <input type="tel" class="form-control" data-heum-null="false" data-heum-label="연락처"/>
  <input type="text" class="form-control" data-heum-validation="false" data-heum-label="검사안함"/>
  <input type="checkbox" name="checkbox" data-heum-min="1" data-heum-null="false" data-heum-label="체크1" data-heum-group-label="체크박스"/>
  <input type="checkbox" name="checkbox" data-heum-label="체크2"/>
  <input type="radio" name="radio" data-heum-label="라디오1" data-heum-group-label="라디오박스"/>
  <input type="radio" name="radio" data-heum-label="라디오2"/>
  <div class="form-group pull-right">
    <div class="btn-group">
      <button type="submit" class="btn btn-primary">전송</button>
      <button type="reset" class="btn btn-warning">초기화</button>
    </div>
  </div>
</form>
```
