
<mb-form>
<mb-quantity default="Cel" path="progress_note/body_temperature/any_event:0/temperature" label="Temperature">
    <mb-unit unit="Cel" label="Cel" min="10" max="50"></mb-unit>
</mb-quantity>
<mb-context path="progress_note/body_temperature/any_event:0/time"></mb-context>
<mb-select path="progress_note/body_temperature/location_of_measurement" label="Location of measurement" terminology="local">
<mb-option value="at0043" label="Skin"></mb-option>
</mb-select>
<mb-context path="progress_note/body_temperature/language"></mb-context>
<mb-context path="progress_note/body_temperature/encoding"></mb-context>
<mb-context path="progress_note/body_temperature/subject"></mb-context>
<mb-context path="progress_note/category"></mb-context>
<mb-context path="progress_note/language"></mb-context>
<mb-context path="progress_note/territory"></mb-context>
<mb-context path="progress_note/composer"></mb-context>
<mb-submit>
    <sl-button>Submit</sl-button>
</mb-submit>
</mb-form>