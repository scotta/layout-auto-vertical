layout-auto-vertical
====================

This element merely wraps the
[auto-vertical sample code](https://www.polymer-project.org/0.5/docs/polymer/layout-attrs.html) provided by the Polymer
project for use within Meteor and other projects in general.

The layout switches from horizontal to vertical when the provided threshold is crossed.

See the [component page](https://github.com/scotta/layout-auto-vertical) for more information.

Example:

    <layout-auto-vertical responsiveWidth="800">
        <div auto-vertical flex one>
            This is 1
        </div>
        <div auto-vertical flex two>
            This is 2
        </div>
        <div auto-vertical>
            This is 3
        </div>
    </layout-auto-vertical>

Note for flexed horizontal layouts
----------------------------------
You *must specify a flex ratio* for all flexed horizontal layout elements. If you fail to specify a ratio the element
 may not be displayed when in the vertical layout.
