# bergmann

Bergmann test tasks

## Test Task No. 1

Please create a single page web application using Angular/Material/Tailwind/rxjs.
The application should be a simple chart widgets dashboard. On a dashboard user can put 1 to 4 charts.

Optional: Make charts as directive.On the top bar it should be possible to set a date period that will be applied to all charts at the same time.

Every chart should be configurable:

> -type: line or bar chart-selection of sensors
> -color of lines For data shown in charts generate random values or use some public data API (optional).

Example: There are N sensors, some of them measure temperature, some -humidity, some -light. We need to show that data on different charts. Sometimes we can combine temperature from 2 sensors and humidity and all in 1 chart.

Other libraries that could be used:

> -angular ui bootstrap or analogue
> -angular ui router or analogue-highcharts or analogue

## Test Task No. 2

Extend the functionality of mat-button.
The button should be inactive if the user lacks permissions.
The user should be informed about this via a tooltip.
The button should be disabled if [isViewerDisabled]='true'.
The tooltip text is set through a separate field (e.g., viewerTooltip).
The new functionality should not conflict with existing features.
Enable the possibility to extend the functionality of any mat-button.

Additionally, button inactivity means:

> The button appears as disabled (https://material.angular.io/components/button/overview)
> When hovering over such a button, the cursor changes to not-allowed (https://css-tricks.com/almanac/properties/c/cursor/)
