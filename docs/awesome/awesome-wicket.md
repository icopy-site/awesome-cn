## Awesome Wicket [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[<img src="https://upload.wikimedia.org/wikipedia/ru/5/5d/Apache_Wicket_logo.png" align="right" width="100">](http://wicket.apache.org/)

A curated list of awesome projects powered by [Apache Wicket](http://wicket.apache.org)

Your contributions are always welcome!

> Wicket is an open source, component oriented, serverside, Java web application framework. With a history of over a decade, it is still going strong and has a solid future ahead. 

## Table of Contents

- [Generic Info](#generic-info)
- [Libraries](#libraries)
  - [WicketStuff](#wicketstuff)
- [Web Frameworks](#web-frameworks)
- [Solutions](#solutions)
- [IDE Plugins and Tools](#ide-plugins-and-tools)

## Generic Info

- [Apache Wicket](http://wicket.apache.org/) - Wicket official site.
- [Wicket on Github](https://github.com/apache/wicket) - Official mirror of Wicket on [GitHub](https://github.com).
- [Wicket on Twitter](https://twitter.com/apache_wicket) - Official account of Wicket.
- [Wicket wiki](https://cwiki.apache.org/confluence/display/WICKET/Index) - Official knowledge base on Wiki about Wicket.
- [Build With Wicket](https://builtwithwicket.tumblr.com/) - Official [Tumblr](https://www.tumblr.com/) account of Wicket.
- [Wicket User Guide](http://ci.apache.org/projects/wicket/guide/7.x/) - Wicket user guide for version 7.x.
- [Wicket JavaDocs](http://ci.apache.org/projects/wicket/apidocs/7.x/index.html) - Wicket JavaDocs for version 7.x.
- [Wicket in Action](http://wicketinaction.com/) - Blog and book about Wicket.

## Libraries
List of libraries and components which can be used in your application

- [wicket-akka](https://github.com/l0rdn1kk0n/wicket-akka) - Integration of Akka for Wicket.
- [wicket-autowire](https://github.com/wicket-acc/wicket-autowire) - Makes your life easier by automatic creation of component according to provided annotation.
- [wicket-bootstrap](https://github.com/l0rdn1kk0n/wicket-bootstrap) - Integration of Bootstrap Toolkit for Wicket.
- [wicket-clientside-logging](https://github.com/l0rdn1kk0n/wicket-clientside-logging) - Helper library that allows javascript logging on client side, all log messages will be stored on server side too.
- [wicket-console](https://github.com/PhantomYdn/wicket-console) - Lightweight AJAX-enabled web console for runtime execution JS scripts on server side.
- [wicket-crudifier](https://github.com/premium-minds/wicket-crudifier) - Library to easily create CRUD's with wicket.
- [wicket-dnd](https://github.com/svenmeier/wicket-dnd) - Generic Drag&Drop framework for Wicket.
- [wicket-extjs-integration](https://github.com/onehippo/wicket-extjs-integration) - Integration of Wicket with ExtJS with event handling and a focus on making the Java-API as close to the JS-API as possible.
- [wicket-fullcalendar](https://github.com/42Lines/wicket-fullcalendar) - Integration of [FullCalendar](http://fullcalendar.io/) javascript lib with Wicket.
- [wicket-jersey](https://github.com/OrienteerBAP/wicket-jersey) - Adapter to run JAR-RX resources on [Jersey2](https://jersey.github.io/) under Wicket.
- [wicket-jquery-selectors](https://github.com/l0rdn1kk0n/wicket-jquery-selectors) - Library for working with JQuery and Wicket.
- [wicket-jquery-ui](http://www.7thweb.net/wicket-jquery-ui/) - JQuery UI integration in Wicket 1.5.x, Wicket 6.x & Wicket7.x.
- [wicket-modelfactory](http://wicketeer.org/wicket-modelfactory/) - Wicket-modelfactory is an API to create Wicket PropertyModels in a typesafe and refactoring-safe way.
- [wicket-mustache](https://github.com/l0rdn1kk0n/wicket-mustache) - Provides a specialized panel and some related utilities that enables users to work with Mustache and Wicket.
- [wicket-orientdb](https://github.com/OrienteerDW/wicket-orientdb) - Integration of Wicket with [OrientDB](http://orientdb.com/).
- [wicket-requirejs](https://github.com/l0rdn1kk0n/wicket-requirejs) - Helper to use require.js in your Wicket application.
- [wicket-shieldui](https://github.com/shieldui/wicket-shieldui) - Components leveraging the use of the [Shield UI](http://www.shieldui.com/) JavaScript library.
- [wicket-source](https://github.com/42Lines/wicket-source) - Speeds up Wicket development by providing click-through from browser HTML back to the original Wicket components in your source.
- [wicket-spring-boot](https://github.com/MarcGiffing/wicket-spring-boot) - Makes it easy to create Wicket projects with a minimum of configuration effort by using Sprint Boot.
- [wicket-webjars](https://github.com/l0rdn1kk0n/wicket-webjars) - Integration of webjars for Wicket.
- [wicked-charts](https://github.com/thombergs/wicked-charts) - Beautiful and interactive javascript charts for Java-based web applications.

### WicketStuff
[WicketStuff](https://github.com/wicketstuff/core) based libraries

- [Annotation](https://github.com/wicketstuff/core/wiki/Annotation) - Mount your pages declarativly by java annotations.
- [Annotation Event Dispatcher](https://github.com/wicketstuff/core/tree/master/annotationeventdispatcher-parent) - Improves events handling in Wicket by annotations.
- [Async Tasks](https://github.com/wicketstuff/core/wiki/Async-tasks) -  Control a background process within a Wicket application.
- [Autocomplete TagIt](https://github.com/wicketstuff/core/wiki/Autocomplete-TagIt) - [TagIt](http://aehlke.github.com/tag-it/) integration with Wicket.
- [BrowserId](https://github.com/wicketstuff/core/wiki/BrowserId) - [Mozilla Persona](https://login.persona.org/) integration with Wicket.
- [Console](https://github.com/wicketstuff/core/wiki/Console) - Provides support for executing code dynamically (at runtime).
- [Context](https://github.com/wicketstuff/core/wiki/Context) - Used to locate components,models and models' objects declaratively with @Context annotation.
- [Dashboard](https://github.com/wicketstuff/core/tree/master/dashboard-parent) - Support of dashboards for Wicket for quick access to required information in widgets.
- [DataStores](https://github.com/wicketstuff/core/wiki/DataStores) - Collection of various implementation of [IDataStore](https://github.com/apache/wicket/blob/master/wicket-core/src/main/java/org/apache/wicket/pageStore/IDataStore.java): [MemCached](http://memcached.org/), [Apache Cassandra](http://cassandra.apache.org/), [Redis](http://redis.io/), [Hazelcast](http://www.hazelcast.com/).
- [Datatable Autocomplete](https://github.com/wicketstuff/core/wiki/Datatable-Autocomplete) - Provides a search data structure known as a [Trie](http://en.wikipedia.org/wiki/Trie) that allows AJAX searches on large datasets fast.
- [DataTables](https://github.com/wicketstuff/core/wiki/DataTables) - [DataTables jQuery](http://www.datatables.net/) Plugin Integration.
- [Editable Grid](https://github.com/wicketstuff/core/wiki/Editable-Grid) - A grid component with add/edit/delete feature all at once, apart from supporting sorting/filtering/paging.
- [Eidogo](https://github.com/wicketstuff/core/wiki/Eidogo) - SGF viewer and editor for GO game (also called baduk, igo or weiqi).
- [Facebook](https://github.com/wicketstuff/core/wiki/Facebook) - Contains wicket components and behaviors to use the [Facebook](https://facebook.com) social plugins with wicket.
- [Fast Serializer](https://github.com/wicketstuff/core/wiki/FastSerializer) - Wicket Serializer using the Fast 1.x (FST) library.
- [Fast Serializer 2](https://github.com/wicketstuff/core/wiki/FastSerializer2) - Wicket Serializer using the Fast 2.x (FST) library.
- [GMap3](https://github.com/wicketstuff/core/wiki/Gmap3) - Offers a component to use Google Maps v3 within Wicket applications.
- [Google AppEngine Initializer](https://github.com/wicketstuff/core/wiki/Google-AppEngine-Initializer) - Provides Wicket's org.apache.wicket.IInitializer implementation that auto-configures the Wicket Application to be runable at Google AppEngine.
- [Google Charts](https://github.com/wicketstuff/core/wiki/GoogleCharts) - Allows creation of charts using the [Google Chart API](https://developers.google.com/chart/).
- [HTML5](https://github.com/wicketstuff/core/wiki/Html5) - Contains classes that give wicket support for using exciting new Html5 features.
- [HTML Compressor](https://github.com/wicketstuff/core/wiki/Htmlcompressor) - Integration library for Wicket and [htmlcompressor](http://code.google.com/p/htmlcompressor).
- [InMethodGrid](https://github.com/wicketstuff/core/wiki/InMethodGrid) - Data grid component.
- [Java EE Inject](https://github.com/wicketstuff/core/wiki/Java-EE-Inject) - Provides integration through Java EE 5 resource injection.
- [JEE Web Integration](https://github.com/wicketstuff/core/wiki/JEE-Web-Integration) - Embed Servlet, JSP abd JSF content into wicked HTML pages.
- [JqPlot Plugin Integration](https://github.com/wicketstuff/core/wiki/JqPlot-Plugin-Integration) - Produces beautiful line, bar and pie charts with many features.
- [JWicket UI Toolip](https://github.com/wicketstuff/core/wiki/jWicket-UI-Tooltip) - Generate the JavaScript needed to provide a Wicket Component with a jQuery UI tooltip.
- [Kryo Serializer](https://github.com/wicketstuff/core/wiki/Kryo-Serializer) - An implementation of org.apache.wicket.serialize.ISerializer for Wicket.
- [Kryo2 Serializer](https://github.com/wicketstuff/core/tree/master/serializer-kryo2) - An implementation of org.apache.wicket.serialize.ISerializer for Wicket.
- [LazyModel](https://github.com/wicketstuff/core/wiki/LazyModel) - Type-safe model implementation.
- [Lightbox2 Plugin Integration](https://github.com/wicketstuff/core/wiki/Lightbox2-Plugin-Integration) - Simple, unobtrusive script used to overlay images on top of the current page.
- [Logback](https://github.com/wicketstuff/core/wiki/Logback) - The home for classes that can help with using wicket and [logback](http://logback.qos.ch/) together.
- [MBeanView](https://github.com/wicketstuff/core/wiki/MBeanView) - JMX panel, to view and operate the applications mbeans.
- [Minis](https://github.com/wicketstuff/core/wiki/Minis) - Collection of assorted components and behaviors that are too small to warrant their own project.
- [ModalX](https://github.com/wicketstuff/core/wiki/ModalX) - A lightweight extension to Wicket's ModalWindow capabilities that comes with standardized MessageBox class and allows easy definition of Modal dialog box classes.
- [OSGI](https://github.com/wicketstuff/core/wiki/Osgi) - Lets you use Wicket in OSGi environments.
- [Open Layers 3](https://github.com/wicketstuff/core/tree/master/openlayers3-parent) - Provides a set of components that may be used to add interactive maps to a Wicket application.
- [POI](https://github.com/wicketstuff/core/wiki/POI) - Integrates Wicket projects to Apache POI.
- [Progressbar](https://github.com/wicketstuff/core/wiki/Progressbar) - Provides a progress bar component for Wicket.
- [Push](https://github.com/wicketstuff/core/wiki/Push) - Provides support for Reverse AJAX in Wicket applications and allows them to "push" partial Web page updates to the Web browser.
- [Scala Extensions](https://github.com/wicketstuff/core/wiki/ScalaExtensions) - Improves the syntax of Wicket models when using the Scala programming language.
- [Select2](https://github.com/wicketstuff/core/tree/master/select2-parent) - Provides Apache Wicket components that leverage [Select2](http://ivaynberg.github.com/select2) JavaScript library to build select boxes that provide Ajax choice filtering, custom rendering and etc.
- [Servlet Container Authentication and Authorization](https://github.com/wicketstuff/core/wiki/Servlet-Container-Authentication-and-Authorization) - Simplify the integration of wicket-auth-roles with the servlet 3 security container.
- [Spring Reference](https://github.com/wicketstuff/core/wiki/SpringReference) - Can be used to integrate a wicket web application with spring.
- [Stateless](https://github.com/wicketstuff/core/tree/master/stateless-parent) - Adds a few components that provide more comprehensive stateless features for Wicket.
- [TinyMCE Integration](https://github.com/wicketstuff/core/wiki/TinyMCE-Integration) - Integration of the well-known TinyMCE WYSIWYG editor in Wicket.
- [Twitter](https://github.com/wicketstuff/core/wiki/Twitter) - Contains wicket components and behaviors to use the Twitter widgets with wicket.
- [UrlFragment](https://github.com/wicketstuff/core/tree/master/urlfragment-parent) - With this you can build bookmarkable AJAX features and still support the back button.
- [WHighCharts](https://github.com/wicketstuff/wiquery-highcharts) - Provides WiQuery bindings for HighCharts.
- [Whiteboard](https://github.com/wicketstuff/core/wiki/Whiteboard) - Provides a Whiteboard which can be integrated in any wicket application.
- [wicket-foundation](https://github.com/wicketstuff/core/tree/master/wicket-foundation) - Integrates Wicket and [Zurb Foundation](http://foundation.zurb.com/).
- [Wicket Rest Annotations](https://github.com/wicketstuff/core/tree/master/wicketstuff-restannotations-parent) - Provides a special resource class and a set of annotations to implement REST API/services in much the same way as we do it with Spring MVC or with the standard JAX-RS.
- [WiQuery](https://github.com/wicketstuff/wiquery) - Wicket integration with jQuery and jQuery UI.
- [WqPlot](https://github.com/wicketstuff/wiquery-jqplot) - Provides WiQuery bindings for JqPlot.

## Web Frameworks
Web Framework on top of wicket which allow you to build your system easily and smoothly

- [Apache Isis](https://isis.apache.org/) - A framework for rapidly developing domain-driven apps in Java.
- [BrixCMS](http://www.brixcms.org/) - Wicket based CMS (seems to be dead).
- [Hippo CMS](http://www.onehippo.com/en) - Enables enterprises to continuously refine their online business strategy by responding quickly to content performance metrics.
- [Nocket](https://github.com/Nocket/nocket) - Naked Object based framework for wicket.
- [NoWicket](http://invesdwin.de/nowicket/) - A naked objects framework for Wicket that enables developers to write less boilerplate Wicket code during implementation of complex websites.
- [Orienteer](https://github.com/OrienteerDW/Orienteer) - Web framework on top of Wicket and [OrientDB](http://orientdb.com/) to build you own CRM, CMS, ERP, mobile app backend or just common site.
- [Wicketopia](https://github.com/jwcarman/Wicketopia) - Rapid Application Development (RAD) library for the Wicket.

## Solutions
End-to-end solution based on wicket and derived [Web Frameworks](#web-frameworks)

- [eFaps](http://www.efaps.org/) - A list od modules and applications that together form the base of a configurable ERP implementation.
- [eHour](https://ehour.nl/index.phtml) - Open source time tracking tool.
- [Estatio](https://github.com/estatio/estatio) - Open source estate management built on Apache Isis and wicket.
- [GeoServer](https://github.com/geoserver/geoserver) - Open source software server written in Java that allows users to share and edit geospatial data.
- [NextReports](http://www.next-reports.com/) - Smart business reportins.
- [Orienteer](https://github.com/OrienteerDW/Orienteer) - Open source Business Application Platform for implementation of data warehouse, CRM, ERP, app/site backend system and other business apps.
- [ProjectForge](https://www.projectforge.org/) - Open source software for your project management.
- [Yes Cart](https://github.com/inspire-software/yes-cart) - Pure e-Commerse platform.

## IDE Plugins and Tools

- [qwickie](https://marketplace.eclipse.org/content/qwickie) - [Eclipse](http://www.eclipse.org/) plugin for the Java Webframework Wicket
- [WicketForge](https://github.com/minman/wicketforge) - IDE plugin for [IntelliJ IDEA](https://www.jetbrains.com/idea/) designed to assist developers creating applications using Apache Wicket.

## License

 [![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
