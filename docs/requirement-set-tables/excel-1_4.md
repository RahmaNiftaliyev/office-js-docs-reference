| Class | Fields | Description |
|:---|:---|:---|
|[BindingCollection](/javascript/api/excel/excel.bindingcollection)|[getCount()](/javascript/api/excel/excel.bindingcollection#getCount__)|Gets the number of bindings in the collection.|
||[getItemOrNullObject(id: string)](/javascript/api/excel/excel.bindingcollection#getItemOrNullObject_id_)|Gets a binding object by ID.|
|[ChartCollection](/javascript/api/excel/excel.chartcollection)|[getCount()](/javascript/api/excel/excel.chartcollection#getCount__)|Returns the number of charts in the worksheet.|
||[getItemOrNullObject(name: string)](/javascript/api/excel/excel.chartcollection#getItemOrNullObject_name_)|Gets a chart using its name.|
|[ChartPointsCollection](/javascript/api/excel/excel.chartpointscollection)|[getCount()](/javascript/api/excel/excel.chartpointscollection#getCount__)|Returns the number of chart points in the series.|
|[ChartSeriesCollection](/javascript/api/excel/excel.chartseriescollection)|[getCount()](/javascript/api/excel/excel.chartseriescollection#getCount__)|Returns the number of series in the collection.|
|[NamedItem](/javascript/api/excel/excel.nameditem)|[comment](/javascript/api/excel/excel.nameditem#comment)|Specifies the comment associated with this name.|
||[delete()](/javascript/api/excel/excel.nameditem#delete__)|Deletes the given name.|
||[getRangeOrNullObject()](/javascript/api/excel/excel.nameditem#getRangeOrNullObject__)|Returns the range object that is associated with the name.|
||[scope](/javascript/api/excel/excel.nameditem#scope)|Specifies if the name is scoped to the workbook or to a specific worksheet.|
||[worksheet](/javascript/api/excel/excel.nameditem#worksheet)|Returns the worksheet on which the named item is scoped to.|
||[worksheetOrNullObject](/javascript/api/excel/excel.nameditem#worksheetOrNullObject)|Returns the worksheet to which the named item is scoped.|
|[NamedItemCollection](/javascript/api/excel/excel.nameditemcollection)|[add(name: string, reference: Range \| string, comment?: string)](/javascript/api/excel/excel.nameditemcollection#add_name__reference__comment_)|Adds a new name to the collection of the given scope.|
||[addFormulaLocal(name: string, formula: string, comment?: string)](/javascript/api/excel/excel.nameditemcollection#addFormulaLocal_name__formula__comment_)|Adds a new name to the collection of the given scope using the user's locale for the formula.|
||[getCount()](/javascript/api/excel/excel.nameditemcollection#getCount__)|Gets the number of named items in the collection.|
||[getItemOrNullObject(name: string)](/javascript/api/excel/excel.nameditemcollection#getItemOrNullObject_name_)|Gets a `NamedItem` object using its name.|
|[PivotTableCollection](/javascript/api/excel/excel.pivottablecollection)|[getCount()](/javascript/api/excel/excel.pivottablecollection#getCount__)|Gets the number of pivot tables in the collection.|
||[getItemOrNullObject(name: string)](/javascript/api/excel/excel.pivottablecollection#getItemOrNullObject_name_)|Gets a PivotTable by name.|
|[Range](/javascript/api/excel/excel.range)|[getIntersectionOrNullObject(anotherRange: Range \| string)](/javascript/api/excel/excel.range#getIntersectionOrNullObject_anotherRange_)|Gets the range object that represents the rectangular intersection of the given ranges.|
||[getUsedRangeOrNullObject(valuesOnly?: boolean)](/javascript/api/excel/excel.range#getUsedRangeOrNullObject_valuesOnly_)|Returns the used range of the given range object.|
|[RangeViewCollection](/javascript/api/excel/excel.rangeviewcollection)|[getCount()](/javascript/api/excel/excel.rangeviewcollection#getCount__)|Gets the number of `RangeView` objects in the collection.|
|[Setting](/javascript/api/excel/excel.setting)|[delete()](/javascript/api/excel/excel.setting#delete__)|Deletes the setting.|
||[key](/javascript/api/excel/excel.setting#key)|The key that represents the ID of the setting.|
||[value](/javascript/api/excel/excel.setting#value)|Represents the value stored for this setting.|
|[SettingCollection](/javascript/api/excel/excel.settingcollection)|[add(key: string, value: string \| number \| boolean \| Date \| Array<any> \| any)](/javascript/api/excel/excel.settingcollection#add_key__value_)|Sets or adds the specified setting to the workbook.|
||[getCount()](/javascript/api/excel/excel.settingcollection#getCount__)|Gets the number of settings in the collection.|
||[getItem(key: string)](/javascript/api/excel/excel.settingcollection#getItem_key_)|Gets a setting entry via the key.|
||[getItemOrNullObject(key: string)](/javascript/api/excel/excel.settingcollection#getItemOrNullObject_key_)|Gets a setting entry via the key.|
||[items](/javascript/api/excel/excel.settingcollection#items)|Gets the loaded child items in this collection.|
||[onSettingsChanged](/javascript/api/excel/excel.settingcollection#onSettingsChanged)|Occurs when the settings in the document are changed.|
|[SettingsChangedEventArgs](/javascript/api/excel/excel.settingschangedeventargs)|[settings](/javascript/api/excel/excel.settingschangedeventargs#settings)|Gets the `Setting` object that represents the binding that raised the settings changed event|
|[TableCollection](/javascript/api/excel/excel.tablecollection)|[getCount()](/javascript/api/excel/excel.tablecollection#getCount__)|Gets the number of tables in the collection.|
||[getItemOrNullObject(key: string)](/javascript/api/excel/excel.tablecollection#getItemOrNullObject_key_)|Gets a table by name or ID.|
|[TableColumnCollection](/javascript/api/excel/excel.tablecolumncollection)|[getCount()](/javascript/api/excel/excel.tablecolumncollection#getCount__)|Gets the number of columns in the table.|
||[getItemOrNullObject(key: number \| string)](/javascript/api/excel/excel.tablecolumncollection#getItemOrNullObject_key_)|Gets a column object by name or ID.|
|[TableRowCollection](/javascript/api/excel/excel.tablerowcollection)|[getCount()](/javascript/api/excel/excel.tablerowcollection#getCount__)|Gets the number of rows in the table.|
|[Workbook](/javascript/api/excel/excel.workbook)|[settings](/javascript/api/excel/excel.workbook#settings)|Represents a collection of settings associated with the workbook.|
|[Worksheet](/javascript/api/excel/excel.worksheet)|[getUsedRangeOrNullObject(valuesOnly?: boolean)](/javascript/api/excel/excel.worksheet#getUsedRangeOrNullObject_valuesOnly_)|The used range is the smallest range that encompasses any cells that have a value or formatting assigned to them.|
||[names](/javascript/api/excel/excel.worksheet#names)|Collection of names scoped to the current worksheet.|
|[WorksheetCollection](/javascript/api/excel/excel.worksheetcollection)|[getCount(visibleOnly?: boolean)](/javascript/api/excel/excel.worksheetcollection#getCount_visibleOnly_)|Gets the number of worksheets in the collection.|
||[getItemOrNullObject(key: string)](/javascript/api/excel/excel.worksheetcollection#getItemOrNullObject_key_)|Gets a worksheet object using its name or ID.|
