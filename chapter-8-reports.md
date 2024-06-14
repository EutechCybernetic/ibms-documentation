# Chapter 8: Reports

This chapter describes the following:

* [Alarm Transaction Report](chapter-8-reports.md#alarm-transaction-report)
* [OPCAE Transaction Report](chapter-8-reports.md#opcae-transaction-report)
* Alarm Reports
  * [Location-wise Alarm Summary Report](chapter-8-reports.md#location-wise-alarm-summary-report)
  * [Severity-wise Alarm Summary Report](chapter-8-reports.md#severity-wise-alarm-summary-report)
  * [Driver Type-wise Alarm Summary Report](chapter-8-reports.md#driver-type-wise-alarm-summary-report)
* [Real-Time Reports](chapter-8-reports.md#real-time-reports)
  * [Configure a Real-Time Report](chapter-8-reports.md#configure-a-real-time-report)
  * [View Real-Time Report](chapter-8-reports.md#view-real-time-reports)

## Alarm Transaction Report

Alarm Transaction report allows you to;

* Filter alarm transactions based on selected **alarmed Equipment** and occurred associated to a particular **Location** within a given time range.
* Sort the filtered Alarm Transactions by Transaction Time/ Equipment/Point/Transaction Message/ User and arrange the sorted transactions in ascending or descending order.

<mark style="color:blue;">**Path**</mark>\
<mark style="color:blue;">**Settings**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">icon</mark>![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAYCAIAAACEIhGsAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxgAADsQB2OOvEAAAALNJREFUSEu9VdEOgCAIzL61tj6prT6wZ78gm5siIqCpPbk4z4MDNdY+C/vt2xHi133yYBddcwSkgGuHZEKBBzP6PYiodCoJMzBrkYhMGZUiamyjyxOKjJqq12kUTVQCEmcaZOZbiO5RainBPq95T6AKDVLQiJLSlKV/1tMZmbnmnIGx2smZ0T1JHWsFkrfUSGcaBHoD0MbBdw80zq3JCUH/Za89Qpw2Bpa8CmTTdngLf95mL07MU8bzyyrxAAAAAElFTkSuQmCC) <mark style="color:blue;">🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Generate**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">section 🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Alarm Transactions Report**</mark>

1. Click the **Settings** icon ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAYCAIAAACEIhGsAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxgAADsQB2OOvEAAAALNJREFUSEu9VdEOgCAIzL61tj6prT6wZ78gm5siIqCpPbk4z4MDNdY+C/vt2xHi133yYBddcwSkgGuHZEKBBzP6PYiodCoJMzBrkYhMGZUiamyjyxOKjJqq12kUTVQCEmcaZOZbiO5RainBPq95T6AKDVLQiJLSlKV/1tMZmbnmnIGx2smZ0T1JHWsFkrfUSGcaBHoD0MbBdw80zq3JCUH/Za89Qpw2Bpa8CmTTdngLf95mL07MU8bzyyrxAAAAAElFTkSuQmCC)on the Home page and select **Alarm Transaction Report** under **Generate** section. **Alarm Transactions** **Report** page will appear.
2. Apply the following **Search filters** to filter the alarm transactions using;
   * **Location:**
     1. Clear the current **location** by clicking![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAASCAIAAADUsmlHAAAABGdBTUEAALGPC/xhBQAAAAlwSFlzAAAOwgAADsIBFShKgAAAABZ0RVh0U29mdHdhcmUAcGFpbnQubmV0IDQuMDvo9WkAAAC/SURBVDhPxZDRCoJAFET7/w8J/0G2N7ewD4h6ELMH2cDWT2h0YLl79xLlSzAMOs5huO7mOM3za5uv8Fb9eTnX7Xp5DL1M8IpQJpSGUaqqPZR4PDAp+Qy+9x17FLBEUijIvl4+tyfZlsInVTZuNvmShBY4rk/SvW8kefRN2YEby+pOKv0/Kb08WCQFXi9/IHFnm9+v+Gz5GUbnavZAMk/8wdUhjLKfLcPJJ5IOviThC6yEkkogM9TLP7mx/K3i9AaSjbTKKfkKuwAAAABJRU5ErkJggg==).
     2. Click **Location** text box and select a location from the drop-down to filter the alarms for that particular location. You may type in a location to filter accordingly.
   * **Asset Category:**
     1. Clear the current **Asset Category** by clicking![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAASCAIAAADUsmlHAAAABGdBTUEAALGPC/xhBQAAAAlwSFlzAAAOwgAADsIBFShKgAAAABZ0RVh0U29mdHdhcmUAcGFpbnQubmV0IDQuMDvo9WkAAAC/SURBVDhPxZDRCoJAFET7/w8J/0G2N7ewD4h6ELMH2cDWT2h0YLl79xLlSzAMOs5huO7mOM3za5uv8Fb9eTnX7Xp5DL1M8IpQJpSGUaqqPZR4PDAp+Qy+9x17FLBEUijIvl4+tyfZlsInVTZuNvmShBY4rk/SvW8kefRN2YEby+pOKv0/Kb08WCQFXi9/IHFnm9+v+Gz5GUbnavZAMk/8wdUhjLKfLcPJJ5IOviThC6yEkkogM9TLP7mx/K3i9AaSjbTKKfkKuwAAAABJRU5ErkJggg==).
     2. Select the required Asset Category to filter the alarms by the selected Asset Category.
   * **Equipment:**
     1. Clear the current **Equipment** by clicking![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAASCAIAAADUsmlHAAAABGdBTUEAALGPC/xhBQAAAAlwSFlzAAAOwgAADsIBFShKgAAAABZ0RVh0U29mdHdhcmUAcGFpbnQubmV0IDQuMDvo9WkAAAC/SURBVDhPxZDRCoJAFET7/w8J/0G2N7ewD4h6ELMH2cDWT2h0YLl79xLlSzAMOs5huO7mOM3za5uv8Fb9eTnX7Xp5DL1M8IpQJpSGUaqqPZR4PDAp+Qy+9x17FLBEUijIvl4+tyfZlsInVTZuNvmShBY4rk/SvW8kefRN2YEby+pOKv0/Kb08WCQFXi9/IHFnm9+v+Gz5GUbnavZAMk/8wdUhjLKfLcPJJ5IOviThC6yEkkogM9TLP7mx/K3i9AaSjbTKKfkKuwAAAABJRU5ErkJggg==).
     2. Select the required Equipment to filter the alarms by the selected Equipment.
   * **Alarm Class:**
     1. By default, “Any” will be selected.
     2. Select the required Alarm Class or multiple Alarm Classes to filter alarms by the selected Alarm Class or Alarm Classes.
   * **Alarm Severity:**
     1. By default, “Any” will be selected.
     2. Select the required Alarm Severity or multiple Alarm Severities to filter alarms by the selected Alarm Severity or Alarm Severities.
   * Use the following filter conditions accordingly.
     1. **Show Cleared alarms**: Shows the alarms that are not in alarmed status and have been cleared.
     2. **Show Disabled alarms**: Shows the alarms that have been disabled manually.
     3. **Show Active alarms:** Shows the active alarms
   * **Date Range:**
     1. **From:** Click **Calendar icon** ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAB0AAAAdCAYAAABWk2cPAAAABGdBTUEAALGPC/xhBQAAAAlwSFlzAAAOwQAADsEBuJFr7QAAABZ0RVh0U29mdHdhcmUAcGFpbnQubmV0IDQuMDvo9WkAAAFuSURBVEhLzVbtjoIwEOz7v9Wd94EK+O15In/Ud9DkTGoGl2jDsKXQHzfJhJTuzoS2bNf8a5zPhf3Zzuxintg8+7Lj77fqiTHeY15Ch6PYL+1kPKpMfEQc4iU1HKfT3qbTDyru43QyssgXqW4oyw0VC2V5WHczjmVYE3oizYHDwBKHUl1qbQ8B9r6mNg9dsXBxKFY0oaYmCvrmoS9WT7T9Fn3AdKAvVg9gzVkg2AdMBzwef5/GqCgsCOwDpgPCRyyNmeUJDYpN+IilMaggLAgMxfV6oTogfMTSGBZQ83b7c8aANtZMQbHUvzSmqXOCtT0NhWbq7Kl2erUvRaV5HYOaqXN68f+wIDCmqfOfArEqUptpoyIBuPFZcCjaTFs7CnbLrFdZEJeLtKHRessAWg0eQm/rghaDJfZl55bFd7d2Jb1DNWBJtEqlESfVu6Qadrt5JcLEG0zeLeIldTheO/ws/axM8MR4u8njdvjxYcwdzu4DnO2k+acAAAAASUVORK5CYII=) or click on the **From** text box and select a start date, month and year starting from when you want to see the Alarm Transactions. Click the **Clock** icon ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAIAAABvFaqvAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxAAADsQBlSsOGwAAAhxJREFUOE+tlf0rQ1EYxzljNpPkbpbsRXkpSmze8gOF8vKLlJ/kfxB/lPyk5BdSCEleMjV5ndr1kma7MplphO/1XMd12J0fdrvbznnO9/mc5zznPGe5cjiU8/NJJpNXYXlzbV2wU7ejq9NV6bVarcJorh6USqWuLy7Xl5b/ROiNnb09FR632Wzmxm8QKHtb26eHR3zM5fW4vV5LoTr581PyUpav5As+Wltf529v4ywNJFAa/L6qmurikhIhtIf7+/OzUHAvQHY9SwMFdnb58ODwkMPpNFhdNBKZn50jAab0tbagwfDBQDoKQsCK8KLB0ZgGk1EXjnDXQMHAPlm7B/qEWOLx+MrCIl409DFCBrHG+nRnd4rCU+gsLzdYkTDExXAHhCm3UVJgR/XbmZEIMVxIBghTYjHqSHYpo7Mg4C6AMH5wfm92Ri53AUTdtf88yHfi8dFAmQFUKn2vd2Zq2oDFcDppHv1J4TPbiopGxkZ5V2BxF0CYZLdrmY8pf0ZuwFK+XABhUpmD/FH0qLj/sEgDMb8nAGHIAqqcxiI3N+nSSXFBiW+09WIYAVGT3eBrIn9sDRVOurh6BvqJAhnEJCN3FYTCQRGTFWVtwCKNUP1UnqbJiXH8SA471qxE1VMeOj55e3+32QoLLBYhNGzTYfBgY2WV7Nisxma/yWRCO9s3JM2QnTubryIL/yK/M5JIPL2+vsCel5ePrBkU9gfZgzJkBRkhrAAAAABJRU5ErkJggg==) and select the **From Time**.
     2. **To:** Click **Calendar icon** ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAB0AAAAdCAYAAABWk2cPAAAABGdBTUEAALGPC/xhBQAAAAlwSFlzAAAOwQAADsEBuJFr7QAAABZ0RVh0U29mdHdhcmUAcGFpbnQubmV0IDQuMDvo9WkAAAFuSURBVEhLzVbtjoIwEOz7v9Wd94EK+O15In/Ud9DkTGoGl2jDsKXQHzfJhJTuzoS2bNf8a5zPhf3Zzuxintg8+7Lj77fqiTHeY15Ch6PYL+1kPKpMfEQc4iU1HKfT3qbTDyru43QyssgXqW4oyw0VC2V5WHczjmVYE3oizYHDwBKHUl1qbQ8B9r6mNg9dsXBxKFY0oaYmCvrmoS9WT7T9Fn3AdKAvVg9gzVkg2AdMBzwef5/GqCgsCOwDpgPCRyyNmeUJDYpN+IilMaggLAgMxfV6oTogfMTSGBZQ83b7c8aANtZMQbHUvzSmqXOCtT0NhWbq7Kl2erUvRaV5HYOaqXN68f+wIDCmqfOfArEqUptpoyIBuPFZcCjaTFs7CnbLrFdZEJeLtKHRessAWg0eQm/rghaDJfZl55bFd7d2Jb1DNWBJtEqlESfVu6Qadrt5JcLEG0zeLeIldTheO/ws/axM8MR4u8njdvjxYcwdzu4DnO2k+acAAAAASUVORK5CYII=) or click on the **To** text box and select an end date, month and year up to when you want to see the Alarm Transactions. Click the **Clock** icon ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAIAAABvFaqvAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxAAADsQBlSsOGwAAAhxJREFUOE+tlf0rQ1EYxzljNpPkbpbsRXkpSmze8gOF8vKLlJ/kfxB/lPyk5BdSCEleMjV5ndr1kma7MplphO/1XMd12J0fdrvbznnO9/mc5zznPGe5cjiU8/NJJpNXYXlzbV2wU7ejq9NV6bVarcJorh6USqWuLy7Xl5b/ROiNnb09FR632Wzmxm8QKHtb26eHR3zM5fW4vV5LoTr581PyUpav5As+Wltf529v4ywNJFAa/L6qmurikhIhtIf7+/OzUHAvQHY9SwMFdnb58ODwkMPpNFhdNBKZn50jAab0tbagwfDBQDoKQsCK8KLB0ZgGk1EXjnDXQMHAPlm7B/qEWOLx+MrCIl409DFCBrHG+nRnd4rCU+gsLzdYkTDExXAHhCm3UVJgR/XbmZEIMVxIBghTYjHqSHYpo7Mg4C6AMH5wfm92Ri53AUTdtf88yHfi8dFAmQFUKn2vd2Zq2oDFcDppHv1J4TPbiopGxkZ5V2BxF0CYZLdrmY8pf0ZuwFK+XABhUpmD/FH0qLj/sEgDMb8nAGHIAqqcxiI3N+nSSXFBiW+09WIYAVGT3eBrIn9sDRVOurh6BvqJAhnEJCN3FYTCQRGTFWVtwCKNUP1UnqbJiXH8SA471qxE1VMeOj55e3+32QoLLBYhNGzTYfBgY2WV7Nisxma/yWRCO9s3JM2QnTubryIL/yK/M5JIPL2+vsCel5ePrBkU9gfZgzJkBRkhrAAAAABJRU5ErkJggg==)and select the **To Time**.
3. To sort the filtered records:
   1. To sort the filtered records based on e.g. Transaction Time/ Equipment, select the required field from the Sort drop-down box.
4. To display the sorted records in ascending or descending order, click the ![](.gitbook/assets/Screenshot\_22.png)icon adjacent to the **Sort** drop-down box accordingly.
   1. &#x20;![](.gitbook/assets/Screenshot\_22.png): Shows that the records are in ascending order as per the selected field from the drop-down box.
   2. ![](.gitbook/assets/Screenshot\_21.png): Shows that the records are in descending order as per the selected field in the drop-down box.
5. Click the![](.gitbook/assets/Screenshot\_14.png)  icon on the toolbar, to display the column names of the Alarm Transaction report. You will observe that alarm list has **Transaction Time, Equipment, Point, Transaction Message** and **User** columns.
6. **Search Alarms** bar allows to search for Alarms using the following fields on report
   * Asset ID (Equipment)
   * Point Name
   * User (Action Taken User)
7. Select the type of the Report format from the **Format** list box and click **Generate** **Report** to generate the report with filtered data.

## OPCAE Transaction Report

OPCAE transaction report is used to view OPCAE event transactions.&#x20;

<mark style="color:blue;">**Path**</mark>\
<mark style="color:blue;">**Settings**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">icon</mark>![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAYCAIAAACEIhGsAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxgAADsQB2OOvEAAAALNJREFUSEu9VdEOgCAIzL61tj6prT6wZ78gm5siIqCpPbk4z4MDNdY+C/vt2xHi133yYBddcwSkgGuHZEKBBzP6PYiodCoJMzBrkYhMGZUiamyjyxOKjJqq12kUTVQCEmcaZOZbiO5RainBPq95T6AKDVLQiJLSlKV/1tMZmbnmnIGx2smZ0T1JHWsFkrfUSGcaBHoD0MbBdw80zq3JCUH/Za89Qpw2Bpa8CmTTdngLf95mL07MU8bzyyrxAAAAAElFTkSuQmCC) <mark style="color:blue;">🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Generate**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">section 🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**OPCAE Transactions Report**</mark>

1. The data can be filtered using the following;
   * **Source** – Source is the ID of the device from which the event triggered
   * **Condition Name** – OPC Event Condition Name
   * **Server ProgID** - Program ID of the OPC server
   * **From and To** – These fields are used to filter the transactions occurred during a given time range
2. To sort the filtered records:
   * To sort the filtered records based on e.g. Source/Transaction Time/ Message, select the required field from the Sort drop-down box.
3. To display the sorted records in ascending or descending order, click the![](.gitbook/assets/Screenshot\_22.png)icon adjacent to the Sort drop-down box accordingly.
   * &#x20;![](.gitbook/assets/Screenshot\_22.png): Shows that the records are in ascending order as per the selected field from the drop-down box.
   * ![](.gitbook/assets/Screenshot\_21.png): Shows that the records are in descending order as per the selected field in the drop-down box.
4. **Export to Exce**l link: Click this link to export OPCAE transaction report to a excel sheet based on the filtered data.

## IBMS Reports

This section explains the following reports which allow you to generate some predefined IBMS reports in PDF/Word/Excel/Excel-raw formats.

1. **Location-wise Alarm Summary Report**
2. **Severity-wise Alarm Summary Report**
3. **Driver Type-wise Alarm Summary Report**

<mark style="color:blue;">**Path**</mark>\
<mark style="color:blue;">**Settings**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">icon</mark>![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAYCAIAAACEIhGsAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxgAADsQB2OOvEAAAALNJREFUSEu9VdEOgCAIzL61tj6prT6wZ78gm5siIqCpPbk4z4MDNdY+C/vt2xHi133yYBddcwSkgGuHZEKBBzP6PYiodCoJMzBrkYhMGZUiamyjyxOKjJqq12kUTVQCEmcaZOZbiO5RainBPq95T6AKDVLQiJLSlKV/1tMZmbnmnIGx2smZ0T1JHWsFkrfUSGcaBHoD0MbBdw80zq3JCUH/Za89Qpw2Bpa8CmTTdngLf95mL07MU8bzyyrxAAAAAElFTkSuQmCC) <mark style="color:blue;">🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Generate**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">section 🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Alarm Reports**</mark>

### Location-wise Alarm Summary Report

This report shows summary of alarms triggered location-wise, within a given time range. Report data will be grouped by the immediate child location of the selected **Site**. After applying the required filters, you can select the report format and click **Generate** to generate the report in selected format.

<mark style="color:blue;">**Path**</mark>\
<mark style="color:blue;">**Settings**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">icon</mark>![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAYCAIAAACEIhGsAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxgAADsQB2OOvEAAAALNJREFUSEu9VdEOgCAIzL61tj6prT6wZ78gm5siIqCpPbk4z4MDNdY+C/vt2xHi133yYBddcwSkgGuHZEKBBzP6PYiodCoJMzBrkYhMGZUiamyjyxOKjJqq12kUTVQCEmcaZOZbiO5RainBPq95T6AKDVLQiJLSlKV/1tMZmbnmnIGx2smZ0T1JHWsFkrfUSGcaBHoD0MbBdw80zq3JCUH/Za89Qpw2Bpa8CmTTdngLf95mL07MU8bzyyrxAAAAAElFTkSuQmCC) <mark style="color:blue;">🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Generate**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">section</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**🡪**</mark> <mark style="color:blue;">**Alarm Reports**</mark><mark style="color:blue;">🡪</mark><mark style="color:blue;">**Location-wise Alarm Summary Report**</mark>

1. Click the **Settings** ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAYCAIAAACEIhGsAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxgAADsQB2OOvEAAAALNJREFUSEu9VdEOgCAIzL61tj6prT6wZ78gm5siIqCpPbk4z4MDNdY+C/vt2xHi133yYBddcwSkgGuHZEKBBzP6PYiodCoJMzBrkYhMGZUiamyjyxOKjJqq12kUTVQCEmcaZOZbiO5RainBPq95T6AKDVLQiJLSlKV/1tMZmbnmnIGx2smZ0T1JHWsFkrfUSGcaBHoD0MbBdw80zq3JCUH/Za89Qpw2Bpa8CmTTdngLf95mL07MU8bzyyrxAAAAAElFTkSuQmCC)icon on the Home page and select **Alarm Reports** under **Generate** section. Reports page will open.
2. On the Reports page, click the **Location Wise Alarm Summary Report** link.
3. Select the appropriate **Site** to filter report data.
4. **From Date:** Select the starting date from which you want the report to include data.
5. **To Date:** Select the ending date up to which you want the report to include data.
6. Select the required **Alarm Stage** _e.g., Escalated._
7. In the **Format** box, select the required format of the report. (E.g. PDF, Word, etc.)
8. Click **Generate Report.** Respective Report will be displayed.

### Severity-wise Alarm Summary Report

This report is to show the summary of alarms of the selected **Severity** which are associated with the selected **Site**. You can select the time range and the **Alarm Stage** as filtering options.

<mark style="color:blue;">**Path**</mark>\
<mark style="color:blue;">**Settings**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">icon</mark>![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAYCAIAAACEIhGsAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxgAADsQB2OOvEAAAALNJREFUSEu9VdEOgCAIzL61tj6prT6wZ78gm5siIqCpPbk4z4MDNdY+C/vt2xHi133yYBddcwSkgGuHZEKBBzP6PYiodCoJMzBrkYhMGZUiamyjyxOKjJqq12kUTVQCEmcaZOZbiO5RainBPq95T6AKDVLQiJLSlKV/1tMZmbnmnIGx2smZ0T1JHWsFkrfUSGcaBHoD0MbBdw80zq3JCUH/Za89Qpw2Bpa8CmTTdngLf95mL07MU8bzyyrxAAAAAElFTkSuQmCC) <mark style="color:blue;">🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Generate**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">section</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**🡪Alarm Reports**</mark><mark style="color:blue;">🡪</mark><mark style="color:blue;">**Severity Wise Alarm Summary Report**</mark>

1. Click the **Settings** ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAYCAIAAACEIhGsAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxgAADsQB2OOvEAAAALNJREFUSEu9VdEOgCAIzL61tj6prT6wZ78gm5siIqCpPbk4z4MDNdY+C/vt2xHi133yYBddcwSkgGuHZEKBBzP6PYiodCoJMzBrkYhMGZUiamyjyxOKjJqq12kUTVQCEmcaZOZbiO5RainBPq95T6AKDVLQiJLSlKV/1tMZmbnmnIGx2smZ0T1JHWsFkrfUSGcaBHoD0MbBdw80zq3JCUH/Za89Qpw2Bpa8CmTTdngLf95mL07MU8bzyyrxAAAAAElFTkSuQmCC)icon on the Home page and select **Alarm Reports** under **Generate** section. Reports page will open.
2. On the Reports page, click the **Severity** **Wise Alarm Summary Report** link.
3. Select the appropriate **Site** to filter report data.
4. **From Date:** Select the starting date from which you want the report to include data.
5. **To Date:** Select the ending date up to which you want the report to include data.
6. **Alarm Severity:** Select the appropriate Alarm Severity to filter report data.
7. Select the required **Alarm Stage** _e.g., Escalated._
8. In the **Format** box, select the required format of the report. (E.g. PDF, Word, etc.)
9. Click **Generate Report.** Respective Report will be displayed.

### Driver Type-wise Alarm Summary Report

This report is to show the summary of alarms of the selected **Driver type,** associated with the selected **Site**. You can select the time range and the **Alarm Stage** as filtering options.

<mark style="color:blue;">**Path**</mark>\
<mark style="color:blue;">**Settings**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">icon</mark>![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAYCAIAAACEIhGsAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxgAADsQB2OOvEAAAALNJREFUSEu9VdEOgCAIzL61tj6prT6wZ78gm5siIqCpPbk4z4MDNdY+C/vt2xHi133yYBddcwSkgGuHZEKBBzP6PYiodCoJMzBrkYhMGZUiamyjyxOKjJqq12kUTVQCEmcaZOZbiO5RainBPq95T6AKDVLQiJLSlKV/1tMZmbnmnIGx2smZ0T1JHWsFkrfUSGcaBHoD0MbBdw80zq3JCUH/Za89Qpw2Bpa8CmTTdngLf95mL07MU8bzyyrxAAAAAElFTkSuQmCC) <mark style="color:blue;">🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Generate**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">section</mark><mark style="color:blue;">**🡪**</mark> <mark style="color:blue;">**Alarm Reports**</mark><mark style="color:blue;">🡪</mark><mark style="color:blue;">**Driver Type Wise Alarm Summary Report**</mark>

1. Click the **Settings** ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAYCAIAAACEIhGsAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxgAADsQB2OOvEAAAALNJREFUSEu9VdEOgCAIzL61tj6prT6wZ78gm5siIqCpPbk4z4MDNdY+C/vt2xHi133yYBddcwSkgGuHZEKBBzP6PYiodCoJMzBrkYhMGZUiamyjyxOKjJqq12kUTVQCEmcaZOZbiO5RainBPq95T6AKDVLQiJLSlKV/1tMZmbnmnIGx2smZ0T1JHWsFkrfUSGcaBHoD0MbBdw80zq3JCUH/Za89Qpw2Bpa8CmTTdngLf95mL07MU8bzyyrxAAAAAElFTkSuQmCC)icon on the Home page and select **Alarm Reports** under **Generate** section. Reports page will open.
2. On the Reports page, click the **Driver Type** **Wise Alarm Summary Report** link.
3. Select the appropriate **Site** to filter report data.
4. **From Date**: Select the starting date from which you want the report to include data.
5. **To Date:** Select the ending date up to which you want the report to include data.
6. **Driver Type:** Select the required Driver Type to filter report data.
7. Select the required **Alarm Stage** _e.g., Escalated._
8. In the **Format** box, select the required format of the report. (E.g. PDF, Word, etc.)
9. Click **Generate Report**. Respective Report will be displayed.

## Real-Time Reports

Real-Time Reports allow you to view Real-Time point values of a selected set of equipment. Before you view a Real-Time report, you need to configure the required Real-Time Report, by selecting the required set of equipment points.

This section describes the following;

1. [Configure a Real-Time Report](chapter-8-reports.md#configure-a-real-time-report)
2. [View Real-Time Report](chapter-8-reports.md#view-real-time-reports)

### Configure a Real-Time Report

This describes how to configure a Real-Time Report.

<mark style="color:blue;">**Path**</mark>\
<mark style="color:blue;">**Settings**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">icon</mark>![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAYCAIAAACEIhGsAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxgAADsQB2OOvEAAAALNJREFUSEu9VdEOgCAIzL61tj6prT6wZ78gm5siIqCpPbk4z4MDNdY+C/vt2xHi133yYBddcwSkgGuHZEKBBzP6PYiodCoJMzBrkYhMGZUiamyjyxOKjJqq12kUTVQCEmcaZOZbiO5RainBPq95T6AKDVLQiJLSlKV/1tMZmbnmnIGx2smZ0T1JHWsFkrfUSGcaBHoD0MbBdw80zq3JCUH/Za89Qpw2Bpa8CmTTdngLf95mL07MU8bzyyrxAAAAAElFTkSuQmCC) <mark style="color:blue;">🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Configure**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">section 🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Real-Time Reports**</mark>

1. Click the **Settings** icon ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAYCAIAAACEIhGsAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxgAADsQB2OOvEAAAALNJREFUSEu9VdEOgCAIzL61tj6prT6wZ78gm5siIqCpPbk4z4MDNdY+C/vt2xHi133yYBddcwSkgGuHZEKBBzP6PYiodCoJMzBrkYhMGZUiamyjyxOKjJqq12kUTVQCEmcaZOZbiO5RainBPq95T6AKDVLQiJLSlKV/1tMZmbnmnIGx2smZ0T1JHWsFkrfUSGcaBHoD0MbBdw80zq3JCUH/Za89Qpw2Bpa8CmTTdngLf95mL07MU8bzyyrxAAAAAElFTkSuQmCC) and select **Real-Time Reports** under **Configure** section. Real-Time Reports search page appears.
2. Click **Add a new Real-Time Report** link.
3. In the **Real-Time Report Name** box, type a suitable name for the new Real-Time Report.
4. Click **Create**. Real-Time Report configuration detailed page will appear.

#### Add Subsystem Point/ Add Calculated Point

1. Real-Time Report configuration **detailed page 🡪Points** tab.
2. Click the **Add** icon![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAB4AAAAdCAIAAAAyxktbAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwgAADsUBWmncRwAAAfhJREFUSEu1lllPg1AQhXvZGkNBW6lafTEucYkm/v9fYaKpGpf0ydZQaGWJadk8CF4LBUKhNn0AMvPNYe5cziWGMWr8z48UoH3ft23bNKzZbO55nuu4HM+xLNtsCpLcEkWRYZgCVdlogMaqPplMG0GQm0xIu72ldDsolhmTgTYMczT88D2/TJ8IQ3r7e7IsLQen0aqqaapWBroYs610ujtKKivRrGpcELWxjtxctGmaFfRSHHLRyUV6rNp13eH7x6p9SMVjhcChD2O0rk2K1+3s/Pry6gZ/wmTPA4gggJNAY351fVpTcpQODmjRdajasuyi+V2pZhCYprWA/r1ZCZIXbEMoVf31NVsLNIJQWrhlnh6fAz+xobFWF5fXZeo99O8C31uMxP48Oz+Ne53iliEWxFBauIyoUxOXSCcxLWzI68vAmc+L6Zhrlgsnun9/WxzJC8LxyWHckI2N5hpVU1rYELElrhFNaSFaklqN3wbVrUFISKNzDR+CX9SF/uSDQ10ttgJ8sd5eByWdJU8EwzJHx4ccx/2pxhXu93q7NYWDQLnxhERE+Bt8qDIduSmHTBgY/K2z3a5AR9ayN2Y7+vB9VHb3E7J/UM7RI8mO44zH+ufUKD6HbG7JitLheT7zRcuenjBCnuthr2OhBIGXN6WKp6cK7V5O+QaIDOrF/icMDwAAAABJRU5ErkJggg==).
3. Select **Subsystem Points** or **Calculated Points,** from the popup window.
4. Select the required **Equipment** and the relevant **Point**.
5. Type a name for the Point as the **Display Name.**
6. Click **Add.**
7. Repeat steps 2-6 to add more points.
8. To delete a Point from the Real-Time Report, in the **Points** tab, click the respective **Delete** icon of the Point that you want to delete.



{% hint style="success" %}
_Tip – If you select the_ _**Point**_ _first, respective_ _**Equipment**_ _will be automatically selected under the_ _**Equipment**_ _field._
{% endhint %}



{% hint style="info" %}
_Note –Configured Real-Time Reports will be displayed under **View🡪Real-Time Report** section._
{% endhint %}

#### Edit a Real-Time Report

1. Click the **Settings** icon ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAYCAIAAACEIhGsAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxgAADsQB2OOvEAAAALNJREFUSEu9VdEOgCAIzL61tj6prT6wZ78gm5siIqCpPbk4z4MDNdY+C/vt2xHi133yYBddcwSkgGuHZEKBBzP6PYiodCoJMzBrkYhMGZUiamyjyxOKjJqq12kUTVQCEmcaZOZbiO5RainBPq95T6AKDVLQiJLSlKV/1tMZmbnmnIGx2smZ0T1JHWsFkrfUSGcaBHoD0MbBdw80zq3JCUH/Za89Qpw2Bpa8CmTTdngLf95mL07MU8bzyyrxAAAAAElFTkSuQmCC)and select **Real-Time Reports** under **Configure** section.
2. Search for the required report and click the name of the configured Real-Time Report to go to its detailed page.
3. In the **Details** tab, mouse hover over the **Details** section and click the **Edit** icon.
4. Edit the Real-Time report name if necessary and click **Save**. Click **Cancel** to abort the operation.
5. Go to the **Points** tab, if you want to add more points to the report, edit point details or delete points from the report.

#### Delete a Real-Time Report

1. Click the **Settings** icon ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAYCAIAAACEIhGsAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxgAADsQB2OOvEAAAALNJREFUSEu9VdEOgCAIzL61tj6prT6wZ78gm5siIqCpPbk4z4MDNdY+C/vt2xHi133yYBddcwSkgGuHZEKBBzP6PYiodCoJMzBrkYhMGZUiamyjyxOKjJqq12kUTVQCEmcaZOZbiO5RainBPq95T6AKDVLQiJLSlKV/1tMZmbnmnIGx2smZ0T1JHWsFkrfUSGcaBHoD0MbBdw80zq3JCUH/Za89Qpw2Bpa8CmTTdngLf95mL07MU8bzyyrxAAAAAElFTkSuQmCC) and select **Real-Time Reports** under **Configure** section.
2. Click the name of the configured Real-Time Report to go to its detailed page.
3. To delete the selected Real-Time report, click the **Delete** icon ![](<.gitbook/assets/Screenshot\_11 (1).png>) or click the **Delete this Real-Time Report** link on the Side bar.
4. Confirmation message box appears. Click **Delete** or click ![](<.gitbook/assets/Screenshot\_10 (1) (1).png>)to close the message box.
5. If the respective report is in use by the system, you will not be allowed to delete it.

### View Real Time Reports

This section describes how to view Real-Time Reports based on the respective Real-Time report configuration. There are two ways of accessing a Real-Time Report.

1. Using the **Real-Time Report** link under the **View** section
2. Using the **Real-Time Report** link under the **Configure** section

#### View Real-Time Report using the Link under View Section

1. Click the **Settings** icon ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAYCAIAAACEIhGsAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxgAADsQB2OOvEAAAALNJREFUSEu9VdEOgCAIzL61tj6prT6wZ78gm5siIqCpPbk4z4MDNdY+C/vt2xHi133yYBddcwSkgGuHZEKBBzP6PYiodCoJMzBrkYhMGZUiamyjyxOKjJqq12kUTVQCEmcaZOZbiO5RainBPq95T6AKDVLQiJLSlKV/1tMZmbnmnIGx2smZ0T1JHWsFkrfUSGcaBHoD0MbBdw80zq3JCUH/Za89Qpw2Bpa8CmTTdngLf95mL07MU8bzyyrxAAAAAElFTkSuQmCC) and select **Real-Time Reports** under **View** section.
2. Search for the required Real-Time report.
3. Click the name of the required Real-Time Report. Respective Real-Time report will appear.

#### View Real-Time Report Using the Link Under Configure Section

1. Click the **Settings** icon ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAYCAIAAACEIhGsAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxgAADsQB2OOvEAAAALNJREFUSEu9VdEOgCAIzL61tj6prT6wZ78gm5siIqCpPbk4z4MDNdY+C/vt2xHi133yYBddcwSkgGuHZEKBBzP6PYiodCoJMzBrkYhMGZUiamyjyxOKjJqq12kUTVQCEmcaZOZbiO5RainBPq95T6AKDVLQiJLSlKV/1tMZmbnmnIGx2smZ0T1JHWsFkrfUSGcaBHoD0MbBdw80zq3JCUH/Za89Qpw2Bpa8CmTTdngLf95mL07MU8bzyyrxAAAAAElFTkSuQmCC) and select **Real-Time Reports** under **Configure** section.
2. Search for the required Real-Time report and click the name of the report to go to its detailed page.
3. On the **Points** tab, click the **Real-Time Values** link on the Side bar. Respective Real-Time report will be displayed.

{% hint style="success" %}
_Tip – To view the column titles of the fields on the_ _**Points**_ _tab, click the_ ![](<.gitbook/assets/Screenshot\_14 (1).png>) _icon on the_ _toolbar on the top right corner._
{% endhint %}

{% hint style="info" %}
_Note –On the Real-Time Report, click the_ ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAhCAIAAAA3RD4GAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwgAADsQBQ3LtBgAAAkhJREFUSEtj/PTpBQMtARMtDQeZTXMLGIkJou/fv3/8+OnD+/c/f/2C+JidjU1AUJCfn4+TkxMtDD59+nz//n2goL6+HpAkYMG9u/cuXb6ydcs2XCFpb29nZWWhpKwEUQB0yto16w8ePARkz54zA58FL168XLN67cWLl4iJJKBjQ0KDgR6Cm07AAqC5UyZPw2q0t48XLg8BrUF2EE4fHD50ZNGiJWimx8XFaGlrCQsLQcTfvn137eo1TGXIurBbcOP6jd7eCcjqgKHs6eUBNxpZCmjN9m07ICGOCSAWoCRTYALAND04JBCr6UDNQHE/f1/8kYRiwcULF9FUA03HTIhwNcA0s2njZmItAKpGC9PKyjL8piOnGVzWoOeDx4+fXL9+/du371xcnG5urri0Iad3XGoI5ANikj8xamheFo1aQDAaaB5EiGS6YcMmPM4BplpbWxs82QJYgr19905YSAi5yEIprlNTMvBY0NHZhqvAAOoClu21NfVw7cDiC14EEBVE+E0HZjpgzYHsOB5eHrhfCVuA33SguYcPH0Grl4CBCbePsAXAAhnoRqyhBxQHxtzqVSjOz8nNQg5MRCTjjwOgNjU1VbjHgUbfunUbs9YD1ku2dgjnkxDJEB8AYw8Yvl8+f8FayWCajtMCYLi/fvUKrfLBn6eKiws0NDUw1WAJInisQsIBmMDxtC2AFT0wTJBDD80OhAUQU2RkZDDTO7Du/fjhw+cvX5A18/Lw8AsI4MkcEMVEtewIFjh4FBBOppSYDtQ79C0AALmOIxYHuBBTAAAAAElFTkSuQmCC)icon to enable **Auto Refresh.** If the Auto Refresh is enabled, the Real-Time Report will be refreshed automatically once changes occur in Real-Time point configuration.\
![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACIAAAAaCAIAAABdDBlVAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwgAADsMBDDN7wQAAAkJJREFUSEtj/PTpBQMR4Ovfr+/+vn/95+2Pfz8gyjmYOERZhIWYBbmZudEMeP/nw/UfN4GCVjzmEClGgtZc/X7jxLdTi9+twOUYP34vd14XbU4NiAKgg2a+nb/p4zYg+4AqiCRgzeNfT6a/mXvs60kifMtgxW2eKZIM9BzcDqKsOfblZNXzRqwWxApF4PIc0DJkZxHwzZaPO3peTUKzo0Qsz5TLSJxVDCL+8ver09/OYSpD1oXPmnPfLhY9rURWDQz9aMEwuAXIUkDLlr5fBYkJTAC3hgkzkWDakS6ciNUOoF6geKJQDMHIQ7fm6NcTaHqAdmAmWbgaYLqa/24JadYA9aCF9VSZPvx2IKcrPJZhyTd3ft47++3Cl39feJh4wgWDcGlGzh+41BCVbwgGBfEK0OOGeJ0kqRy1hqTggiimU6ChJOi5bxfhcSkwffvwuePJRsCS8OWfV+IsYshFH8RAFGscbnvhsWalwgJcRQ5QF7DWiH2YBtcOLAaRiw9iAw2/HcCsCqyZkJ3Iz8yH7G+irMFvB9D0LZ92otV+PnweyLYSZQ2wqAe6F2t4AsWBMTr9zRxk2TbJerTgJcoaYHXifS8UWJ8iWwZkA0WA4mg1KbD2g7c04HaTkAQgeoBxCwz3j38/Ya3KgHb48KMEF4GUBoyPp7+fo1Vx+DNmn3S7EZc+VjXYfQOPc2DIXPx+ZcunHXjaN8BmBjDC9Tl18GQpFGuAYQ10izK7Imb+ANb5b/68+/j3I2qq5RdhEcKTmeCKAVWYInGaIj25AAAAAElFTkSuQmCC) Icon shows that the Auto Refresh is enabled. Click it to disable Auto Refresh feature.
{% endhint %}
