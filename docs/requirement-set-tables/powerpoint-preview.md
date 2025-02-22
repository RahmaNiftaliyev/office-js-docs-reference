| Class | Fields | Description |
|:---|:---|:---|
|[AddSlideOptions](/javascript/api/powerpoint/powerpoint.addslideoptions)|[layoutId](/javascript/api/powerpoint/powerpoint.addslideoptions#layoutId)|Specifies the ID of a Slide Layout to be used for the new slide.|
||[slideMasterId](/javascript/api/powerpoint/powerpoint.addslideoptions#slideMasterId)|Specifies the ID of a Slide Master to be used for the new slide.|
|[Presentation](/javascript/api/powerpoint/powerpoint.presentation)|[slideMasters](/javascript/api/powerpoint/powerpoint.presentation#slideMasters)|Returns the collection of `SlideMaster` objects that are in the presentation.|
||[tags](/javascript/api/powerpoint/powerpoint.presentation#tags)|Returns a collection of tags attached to the presentation.|
|[Shape](/javascript/api/powerpoint/powerpoint.shape)|[delete()](/javascript/api/powerpoint/powerpoint.shape#delete__)|Deletes the shape from the shape collection.|
||[id](/javascript/api/powerpoint/powerpoint.shape#id)|Gets the unique ID of the shape.|
||[tags](/javascript/api/powerpoint/powerpoint.shape#tags)|Returns a collection of tags in the shape.|
|[ShapeCollection](/javascript/api/powerpoint/powerpoint.shapecollection)|[getCount()](/javascript/api/powerpoint/powerpoint.shapecollection#getCount__)|Gets the number of shapes in the collection.|
||[getItem(key: string)](/javascript/api/powerpoint/powerpoint.shapecollection#getItem_key_)|Gets a shape using its unique ID.|
||[getItemAt(index: number)](/javascript/api/powerpoint/powerpoint.shapecollection#getItemAt_index_)|Gets a shape using its zero-based index in the collection.|
||[getItemOrNullObject(id: string)](/javascript/api/powerpoint/powerpoint.shapecollection#getItemOrNullObject_id_)|Gets a shape using its unique ID.|
||[items](/javascript/api/powerpoint/powerpoint.shapecollection#items)|Gets the loaded child items in this collection.|
|[Slide](/javascript/api/powerpoint/powerpoint.slide)|[layout](/javascript/api/powerpoint/powerpoint.slide#layout)|Gets the layout of the slide.|
||[shapes](/javascript/api/powerpoint/powerpoint.slide#shapes)|Returns a collection of shapes in the slide.|
||[slideMaster](/javascript/api/powerpoint/powerpoint.slide#slideMaster)|Gets the `SlideMaster` object that represents the slide's default content.|
||[tags](/javascript/api/powerpoint/powerpoint.slide#tags)|Returns a collection of tags in the slide.|
|[SlideCollection](/javascript/api/powerpoint/powerpoint.slidecollection)|[add(options?: PowerPoint.AddSlideOptions)](/javascript/api/powerpoint/powerpoint.slidecollection#add_options_)|Adds a new slide at the end of the collection.|
|[SlideLayout](/javascript/api/powerpoint/powerpoint.slidelayout)|[id](/javascript/api/powerpoint/powerpoint.slidelayout#id)|Gets the unique ID of the slide layout.|
||[name](/javascript/api/powerpoint/powerpoint.slidelayout#name)|Gets the name of the slide layout.|
|[SlideLayoutCollection](/javascript/api/powerpoint/powerpoint.slidelayoutcollection)|[getCount()](/javascript/api/powerpoint/powerpoint.slidelayoutcollection#getCount__)|Gets the number of layouts in the collection.|
||[getItem(key: string)](/javascript/api/powerpoint/powerpoint.slidelayoutcollection#getItem_key_)|Gets a layout using its unique ID.|
||[getItemAt(index: number)](/javascript/api/powerpoint/powerpoint.slidelayoutcollection#getItemAt_index_)|Gets a layout using its zero-based index in the collection.|
||[getItemOrNullObject(id: string)](/javascript/api/powerpoint/powerpoint.slidelayoutcollection#getItemOrNullObject_id_)|Gets a layout using its unique ID.|
||[items](/javascript/api/powerpoint/powerpoint.slidelayoutcollection#items)|Gets the loaded child items in this collection.|
|[SlideMaster](/javascript/api/powerpoint/powerpoint.slidemaster)|[id](/javascript/api/powerpoint/powerpoint.slidemaster#id)|Gets the unique ID of the Slide Master.|
||[layouts](/javascript/api/powerpoint/powerpoint.slidemaster#layouts)|Gets the collection of layouts provided by the Slide Master for slides.|
||[name](/javascript/api/powerpoint/powerpoint.slidemaster#name)|Gets the unique name of the Slide Master.|
|[SlideMasterCollection](/javascript/api/powerpoint/powerpoint.slidemastercollection)|[getCount()](/javascript/api/powerpoint/powerpoint.slidemastercollection#getCount__)|Gets the number of Slide Masters in the collection.|
||[getItem(key: string)](/javascript/api/powerpoint/powerpoint.slidemastercollection#getItem_key_)|Gets a Slide Master using its unique ID.|
||[getItemAt(index: number)](/javascript/api/powerpoint/powerpoint.slidemastercollection#getItemAt_index_)|Gets a Slide Master using its zero-based index in the collection.|
||[getItemOrNullObject(id: string)](/javascript/api/powerpoint/powerpoint.slidemastercollection#getItemOrNullObject_id_)|Gets a Slide Master using its unique ID.|
||[items](/javascript/api/powerpoint/powerpoint.slidemastercollection#items)|Gets the loaded child items in this collection.|
|[Tag](/javascript/api/powerpoint/powerpoint.tag)|[key](/javascript/api/powerpoint/powerpoint.tag#key)|Gets the unique ID of the tag.|
||[value](/javascript/api/powerpoint/powerpoint.tag#value)|Gets the value of the tag.|
|[TagCollection](/javascript/api/powerpoint/powerpoint.tagcollection)|[add(key: string, value: string)](/javascript/api/powerpoint/powerpoint.tagcollection#add_key__value_)|Adds a new tag at the end of the collection.|
||[delete(key: string)](/javascript/api/powerpoint/powerpoint.tagcollection#delete_key_)|Deletes the tag with the given `key` in this collection.|
||[getCount()](/javascript/api/powerpoint/powerpoint.tagcollection#getCount__)|Gets the number of tags in the collection.|
||[getItem(key: string)](/javascript/api/powerpoint/powerpoint.tagcollection#getItem_key_)|Gets a tag using its unique ID.|
||[getItemAt(index: number)](/javascript/api/powerpoint/powerpoint.tagcollection#getItemAt_index_)|Gets a tag using its zero-based index in the collection.|
||[getItemOrNullObject(key: string)](/javascript/api/powerpoint/powerpoint.tagcollection#getItemOrNullObject_key_)|Gets a tag using its unique ID.|
||[items](/javascript/api/powerpoint/powerpoint.tagcollection#items)|Gets the loaded child items in this collection.|
