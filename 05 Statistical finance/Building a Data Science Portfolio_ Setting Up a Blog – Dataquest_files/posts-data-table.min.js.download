/*!
 * Posts Table with Search & Sort 1.1.5
 * Copyright 2016-2019 Barn2 Media Ltd
 */
(function(n){n(document).ready(function(){var t=n(".posts-data-table"),e=n("#wpadminbar").length;t.each(function(){var t={responsive:!0,processing:!0};"undefined"!=typeof posts_data_table&&posts_data_table.langurl&&(t.language={url:posts_data_table.langurl});var a=n(this).DataTable(t);n(this).on("page.dt",function(){if(!1!==n(this).data("scroll-offset")){var t=n(this).parent().offset().top-n(this).data("scroll-offset");e&&(t-=32),n("html,body").animate({scrollTop:t},300)}}),n(this).data("click-filter")&&a.columns(["category:name","author:name"]).nodes().to$().each(function(){n(this).children("a").on("click",function(){return a.search(n(this).text()).draw(),!1})})})})})(jQuery);