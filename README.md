# Material Navigation
Android Material Navigation (ActionBar, Navigation Drawer, Tabs, CardView, ViewPager)


# Components of Material Navigation:
- Support for Android API 8+
- ActionBar
- Navigation Drawer (with indicator animation)
- Dynamic Drawer menu items with header (array from strings.xml)
- Dynamic Tabs (customized SlidingTabs of Google/iosched)
- CardView
- ViewPager
- Fragmentation (for ViewPager)
- AppCompat Activity


# Improvements:
- Disabled activity re-creation on screen orientation changed
- No deprecation messages (for now)
- No Lint warnings (except RTL support, it is available for API 17+)
- No need extra library
- All colors defined in colors.xml
- All styles defined in styles.xml
- All texts defined in strings.xml (ready for Localizing)
- Moreover all of them in one activity


##Screenshots

###Android 5.1

![Alt text](/screenshots/1.png?raw=true "Android Material Navigation")
![Alt text](/screenshots/2.png?raw=true "Android Material Navigation")
![Alt text](/screenshots/3.png?raw=true "Android Material Navigation")


###Android 2.3.7

![Alt text](/screenshots/4.png?raw=true "Android Material Navigation")


# Customizations:
Change indicator color:

in setTabs method of Main Activity

``` java
slidingTabLayout.setCustomTabColorizer(new SlidingTabLayout.TabColorizer() {
	@Override
	public int getIndicatorColor(int position) {
		return Color.RED;
	}
});
```


#Developed By

* Mustafa OZCAN - http://mustafaozcan.net


#License

    Copyright 2015 Mustafa OZCAN

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
