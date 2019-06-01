# dark-slack
document.addEventListener('DOMContentLoaded', function () {
    $.ajax({
        url: 'https://raw.githubusercontent.com/dyvosvit/dark-slack/master/black.css',
        success: function (css) {
            $("<style></style>").appendTo('head').html(css);
        }
    });
});
# to src/static/ssb-interop.js
