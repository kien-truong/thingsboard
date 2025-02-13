#### Custom action (with HTML template) function

<div class="divider"></div>
<br/>

*function ($event, widgetContext, entityId, entityName, htmlTemplate, additionalParams, entityLabel): void*

A JavaScript function performing custom action with defined HTML template to render dialog.

**Parameters:**

<ul>
  <li><b>$event:</b> <code><a href="https://developer.mozilla.org/en-US/docs/Web/API/MouseEvent" target="_blank">MouseEvent</a></code> - The <a href="https://developer.mozilla.org/en-US/docs/Web/API/MouseEvent" target="_blank">MouseEvent</a> object. Usually a result of a mouse click event.
  </li>
  <li><b>widgetContext:</b> <code><a href="https://github.com/thingsboard/thingsboard/blob/5bb6403407aa4898084832d6698aa9ea6d484889/ui-ngx/src/app/modules/home/models/widget-component.models.ts#L107" target="_blank">WidgetContext</a></code> - A reference to <a href="https://github.com/thingsboard/thingsboard/blob/5bb6403407aa4898084832d6698aa9ea6d484889/ui-ngx/src/app/modules/home/models/widget-component.models.ts#L107" target="_blank">WidgetContext</a> that has all necessary API 
     and data used by widget instance.
  </li>
  <li><b>entityId:</b> <code>string</code> - An optional string id of the target entity.
  </li>
  <li><b>entityName:</b> <code>string</code> - An optional string name of the target entity.
  </li>
  <li><b>htmlTemplate:</b> <code>string</code> - An optional HTML template string defined in <b>HTML</b> tab.<br/> Used to render custom dialog (see <b>Examples</b> for more details).
  </li>
  {% include widget/action/custom_additional_params %}
  <li><b>entityLabel:</b> <code>string</code> - An optional string label of the target entity.
  </li>
</ul>

<div class="divider"></div>

##### Examples

###### Display dialog to create a device or an asset

<br>

<div style="padding-left: 64px;"
     tb-help-popup="widget/action/examples/custom_pretty_create_dialog_js"
     tb-help-popup-placement="top"
     [tb-help-popup-style]="{maxHeight: '50vh', maxWidth: '50vw'}"
     trigger-text="JavaScript function">
</div>

<br>

<div style="padding-left: 64px;"
     tb-help-popup="widget/action/examples/custom_pretty_create_dialog_html"
     tb-help-popup-placement="top"
     [tb-help-popup-style]="{maxHeight: '50vh', maxWidth: '50vw'}"
     trigger-text="HTML code">
</div>

###### Display dialog to edit a device or an asset

<br>

<div style="padding-left: 64px;"
     tb-help-popup="widget/action/examples/custom_pretty_edit_dialog_js"
     tb-help-popup-placement="top"
     [tb-help-popup-style]="{maxHeight: '50vh', maxWidth: '50vw'}"
     trigger-text="JavaScript function">
</div>

<br>

<div style="padding-left: 64px;"
     tb-help-popup="widget/action/examples/custom_pretty_edit_dialog_html"
     tb-help-popup-placement="top"
     [tb-help-popup-style]="{maxHeight: '50vh', maxWidth: '50vw'}"
     trigger-text="HTML code">
</div>

<br>
<br>
