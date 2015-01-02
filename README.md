heumValidation
==============
Jquery plugin Validation

you can see <a href="http://kwangheum.github.io/heumValidation/v2/validation.html">live demo</a>.


## Example

```javascript
$(document).ready(function(){
  $("form").heumValidation();
});

```
```html
<form style="margin-bottom: 50px;">
	<label>min-length</label>
	<input type="text" class="form-control" data-min-length="5"/>
	<label>max-length</label>
	<input type="text" class="form-control" data-max-length="5"/>
	<label>null</label>
	<input type="text" class="form-control" data-null="false"/>
	<label>number</label>
	<input type="number" class="form-control" data-number="true"/>
	<label>email</label>
	<input type="email" class="form-control" data-email="true"/>
	<label>phone</label>
	<input type="tel" class="form-control" data-phone="true"/>
	<label>url</label>
	<input type="url" class="form-control" data-url="true"/>
	<label>pattern</label>
	<input type="text" class="form-control" data-pattern="[a-zA-Z]" data-message="영어만 작성해주세요"/>
	<label>checkbox</label>
	<br/>
	<label>
		<input type="checkbox" name="checkbox" data-null="false" data-min-length="2" data-max-length="3"/>체크
	</label>
	<label>
		<input type="checkbox" name="checkbox" data-null="false" data-min-length="2" data-max-length="3"/>체크
	</label>
	<label>
		<input type="checkbox" name="checkbox" data-null="false" data-min-length="2" data-max-length="3"/>체크
	</label>
	<label>
		<input type="checkbox" name="checkbox" data-null="false" data-min-length="2" data-max-length="3"/>체크
	</label>
	<br/>
	<label>radio</label>
	<br/>
	<label>
		<input type="radio" name="radio" data-null="false"/>라디오
	</label>
	<label>
		<input type="radio" name="radio" data-null="false"/>라디오
	</label>
	<div class="form-group pull-right" style="padding: 20px;">
		<div class="btn-group">
			<button type="submit" class="btn btn-primary">전송</button>
			<button type="reset" class="btn btn-warning">초기화</button>
		</div>
	</div>
</form>
```
