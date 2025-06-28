---
created: 2025-06-27 20:21
modified: 2025-06-27 20:38
---
```

[ 2025-07-27 20:33:34 ]
Logged from: \backend\startup.php [ Line #: 37 ] 
{
    "URI": "\/",
    "microtime": 1751074414.43493,
    "message": "startup ",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 Log::checkpoint() - [\\backend\\startup.php(37)]"
    ]
}

[ 2025-07-27 20:33:34 ]
Logged from: \backend\Binder\Library\SQL\Builders\MySQLBuilder.php [ Line #: 91 ] 
{
    "URI": "\/",
    "microtime": 1751074414.476853,
    "message": "MySQLBuilder built: SELECT * FROM admin_table; ",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 SessionManager->init() - [\\backend\\startup.php(139)]",
        "#2 Auth::orize() - [\\backend\\Binder\\Library\\Utilities\\Session\\SessionManager.php(133)]",
        "#3 Auth::getSessionUserAccessLevel() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(61)]",
        "#4 Auth::getUserAccessLevel() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(128)]",
        "#5 SQLSet->where() - [\\backend\\Binder\\Library\\Utilities\\Traits\\UserAccessFunctions.php(15)]",
        "#6 SQLSet->fetchAll() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(133)]",
        "#7 Database->read() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(149)]",
        "#8 MySQLBuilder::buildSelect() - [\\backend\\Binder\\Library\\SQL\\Database.php(102)]",
        "#9 Log::checkpoint() - [\\backend\\Binder\\Library\\SQL\\Builders\\MySQLBuilder.php(91)]"
    ]
}

[ 2025-07-27 20:33:34 ]
Logged from: \backend\Binder\Library\SQL\Builders\MySQLBuilder.php [ Line #: 91 ] 
{
    "URI": "\/",
    "microtime": 1751074414.48588,
    "message": "MySQLBuilder built: SELECT * FROM admin_table; ",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 SessionManager->init() - [\\backend\\startup.php(139)]",
        "#2 Auth::orize() - [\\backend\\Binder\\Library\\Utilities\\Session\\SessionManager.php(137)]",
        "#3 Auth::getSessionUserACL() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(67)]",
        "#4 Auth::getPageACL() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(141)]",
        "#5 SQLSet->where() - [\\backend\\Binder\\Library\\Utilities\\Traits\\PageAccessFunctions.php(19)]",
        "#6 SQLSet->fetchAll() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(133)]",
        "#7 Database->read() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(149)]",
        "#8 MySQLBuilder::buildSelect() - [\\backend\\Binder\\Library\\SQL\\Database.php(102)]",
        "#9 Log::checkpoint() - [\\backend\\Binder\\Library\\SQL\\Builders\\MySQLBuilder.php(91)]"
    ]
}

[ 2025-07-27 20:33:34 ]
Logged from: \backend\Binder\Library\SQL\Builders\MySQLBuilder.php [ Line #: 91 ] 
{
    "URI": "\/",
    "microtime": 1751074414.491934,
    "message": "MySQLBuilder built: SELECT * FROM page_access; ",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 SessionManager->init() - [\\backend\\startup.php(139)]",
        "#2 Auth::orize() - [\\backend\\Binder\\Library\\Utilities\\Session\\SessionManager.php(137)]",
        "#3 Auth::getSessionUserACL() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(67)]",
        "#4 Auth::getPageACL() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(141)]",
        "#5 SQLSet->where() - [\\backend\\Binder\\Library\\Utilities\\Traits\\PageAccessFunctions.php(25)]",
        "#6 SQLSet->fetchAll() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(133)]",
        "#7 Database->read() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(149)]",
        "#8 MySQLBuilder::buildSelect() - [\\backend\\Binder\\Library\\SQL\\Database.php(102)]",
        "#9 Log::checkpoint() - [\\backend\\Binder\\Library\\SQL\\Builders\\MySQLBuilder.php(91)]"
    ]
}

[ 2025-07-27 20:33:34 ]
Logged from: \backend\Binder\Library\SQL\Builders\MySQLBuilder.php [ Line #: 91 ] 
{
    "URI": "\/",
    "microtime": 1751074414.511806,
    "message": "MySQLBuilder built: SELECT * FROM page_table; ",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 SessionManager->init() - [\\backend\\startup.php(139)]",
        "#2 Auth::orize() - [\\backend\\Binder\\Library\\Utilities\\Session\\SessionManager.php(137)]",
        "#3 Auth::getSessionUserACL() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(67)]",
        "#4 Auth::getPageACL() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(141)]",
        "#5 Auth::pagesByAdminAccess() - [\\backend\\Binder\\Library\\Utilities\\Traits\\PageAccessFunctions.php(39)]",
        "#6 SQLSet->fetchAll() - [\\backend\\Binder\\Library\\Utilities\\Traits\\PageAccessFunctions.php(92)]",
        "#7 Database->read() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(149)]",
        "#8 MySQLBuilder::buildSelect() - [\\backend\\Binder\\Library\\SQL\\Database.php(102)]",
        "#9 Log::checkpoint() - [\\backend\\Binder\\Library\\SQL\\Builders\\MySQLBuilder.php(91)]"
    ]
}

[ 2025-07-27 20:33:34 ]
Logged from: \backend\Binder\Library\SQL\Builders\MySQLBuilder.php [ Line #: 91 ] 
{
    "URI": "\/",
    "microtime": 1751074414.555059,
    "message": "MySQLBuilder built: SELECT * FROM page_access; ",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 SessionManager->init() - [\\backend\\startup.php(139)]",
        "#2 Auth::orize() - [\\backend\\Binder\\Library\\Utilities\\Session\\SessionManager.php(137)]",
        "#3 Auth::getSessionUserACL() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(67)]",
        "#4 Auth::getPageACL() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(141)]",
        "#5 Auth::pagesByGroupAndType() - [\\backend\\Binder\\Library\\Utilities\\Traits\\PageAccessFunctions.php(44)]",
        "#6 SQLSet->fetchAll() - [\\backend\\Binder\\Library\\Utilities\\Traits\\PageAccessFunctions.php(107)]",
        "#7 Database->read() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(149)]",
        "#8 MySQLBuilder::buildSelect() - [\\backend\\Binder\\Library\\SQL\\Database.php(102)]",
        "#9 Log::checkpoint() - [\\backend\\Binder\\Library\\SQL\\Builders\\MySQLBuilder.php(91)]"
    ]
}

[ 2025-07-27 20:33:34 ]
Logged from: \backend\Binder\Library\SQL\Builders\MySQLBuilder.php [ Line #: 91 ] 
{
    "URI": "\/",
    "microtime": 1751074414.570238,
    "message": "MySQLBuilder built: SELECT * FROM user_groups; ",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 SessionManager->init() - [\\backend\\startup.php(139)]",
        "#2 Auth::orize() - [\\backend\\Binder\\Library\\Utilities\\Session\\SessionManager.php(137)]",
        "#3 Auth::getSessionUserACL() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(67)]",
        "#4 Auth::getPageACL() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(141)]",
        "#5 Auth::pagesByGroupAndType() - [\\backend\\Binder\\Library\\Utilities\\Traits\\PageAccessFunctions.php(44)]",
        "#6 SQLSet->fetchAll() - [\\backend\\Binder\\Library\\Utilities\\Traits\\PageAccessFunctions.php(108)]",
        "#7 Database->read() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(149)]",
        "#8 MySQLBuilder::buildSelect() - [\\backend\\Binder\\Library\\SQL\\Database.php(102)]",
        "#9 Log::checkpoint() - [\\backend\\Binder\\Library\\SQL\\Builders\\MySQLBuilder.php(91)]"
    ]
}

[ 2025-07-27 20:33:34 ]
Logged from: \backend\Binder\Library\SQL\Builders\MySQLBuilder.php [ Line #: 91 ] 
{
    "URI": "\/",
    "microtime": 1751074414.572414,
    "message": "MySQLBuilder built: SELECT * FROM user_groups; ",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 SessionManager->init() - [\\backend\\startup.php(139)]",
        "#2 Auth::orize() - [\\backend\\Binder\\Library\\Utilities\\Session\\SessionManager.php(137)]",
        "#3 Auth::getSessionUserACL() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(67)]",
        "#4 Auth::getPageACL() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(141)]",
        "#5 Auth::pagesByGroupAndType() - [\\backend\\Binder\\Library\\Utilities\\Traits\\PageAccessFunctions.php(44)]",
        "#6 SQLSet->where() - [\\backend\\Binder\\Library\\Utilities\\Traits\\PageAccessFunctions.php(111)]",
        "#7 SQLSet->fetchAll() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(133)]",
        "#8 Database->read() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(149)]",
        "#9 MySQLBuilder::buildSelect() - [\\backend\\Binder\\Library\\SQL\\Database.php(102)]",
        "#10 Log::checkpoint() - [\\backend\\Binder\\Library\\SQL\\Builders\\MySQLBuilder.php(91)]"
    ]
}

[ 2025-07-27 20:33:34 ]
Logged from: \backend\Binder\Library\SQL\SQLSet.php [ Line #: 115 ] 
{
    "URI": "\/",
    "microtime": 1751074414.580985,
    "message": "[SQLSet::where() before query runs",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 SessionManager->init() - [\\backend\\startup.php(139)]",
        "#2 Auth::orize() - [\\backend\\Binder\\Library\\Utilities\\Session\\SessionManager.php(137)]",
        "#3 Auth::getSessionUserACL() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(67)]",
        "#4 Auth::getPageACL() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(141)]",
        "#5 SQLSet->where() - [\\backend\\Binder\\Library\\Utilities\\Traits\\PageAccessFunctions.php(54)]",
        "#6 Log::checkpoint() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(115)]"
    ]
}

[ 2025-07-27 20:33:34 ]
Logged from: \backend\Binder\Library\SQL\Builders\MySQLBuilder.php [ Line #: 91 ] 
{
    "URI": "\/",
    "microtime": 1751074414.582113,
    "message": "MySQLBuilder built: SELECT * FROM page_table; ",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 SessionManager->init() - [\\backend\\startup.php(139)]",
        "#2 Auth::orize() - [\\backend\\Binder\\Library\\Utilities\\Session\\SessionManager.php(137)]",
        "#3 Auth::getSessionUserACL() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(67)]",
        "#4 Auth::getPageACL() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(141)]",
        "#5 SQLSet->where() - [\\backend\\Binder\\Library\\Utilities\\Traits\\PageAccessFunctions.php(54)]",
        "#6 SQLSet->fetchAll() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(133)]",
        "#7 Database->read() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(149)]",
        "#8 MySQLBuilder::buildSelect() - [\\backend\\Binder\\Library\\SQL\\Database.php(102)]",
        "#9 Log::checkpoint() - [\\backend\\Binder\\Library\\SQL\\Builders\\MySQLBuilder.php(91)]"
    ]
}

[ 2025-07-27 20:33:34 ]
Logged from: \backend\Binder\Library\SQL\SQLSet.php [ Line #: 140 ] 
{
    "URI": "\/",
    "microtime": 1751074414.616727,
    "message": "[SQLSet::where() after query runs",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 SessionManager->init() - [\\backend\\startup.php(139)]",
        "#2 Auth::orize() - [\\backend\\Binder\\Library\\Utilities\\Session\\SessionManager.php(137)]",
        "#3 Auth::getSessionUserACL() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(67)]",
        "#4 Auth::getPageACL() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(141)]",
        "#5 SQLSet->where() - [\\backend\\Binder\\Library\\Utilities\\Traits\\PageAccessFunctions.php(54)]",
        "#6 Log::checkpoint() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(140)]"
    ]
}

[ 2025-07-27 20:33:34 ]
Logged from: \backend\Binder\Library\SQL\Builders\MySQLBuilder.php [ Line #: 91 ] 
{
    "URI": "\/",
    "microtime": 1751074414.625852,
    "message": "MySQLBuilder built: SELECT * FROM admin_table; ",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 SessionManager->init() - [\\backend\\startup.php(139)]",
        "#2 Auth::orize() - [\\backend\\Binder\\Library\\Utilities\\Session\\SessionManager.php(137)]",
        "#3 Auth::getSessionUserACL() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(67)]",
        "#4 Auth::getFileACL() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(142)]",
        "#5 SQLSet->where() - [\\backend\\Binder\\Library\\Utilities\\Traits\\FileAccessFunctions.php(29)]",
        "#6 SQLSet->fetchAll() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(133)]",
        "#7 Database->read() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(149)]",
        "#8 MySQLBuilder::buildSelect() - [\\backend\\Binder\\Library\\SQL\\Database.php(102)]",
        "#9 Log::checkpoint() - [\\backend\\Binder\\Library\\SQL\\Builders\\MySQLBuilder.php(91)]"
    ]
}

[ 2025-07-27 20:33:34 ]
Logged from: \backend\Binder\Library\SQL\Builders\MySQLBuilder.php [ Line #: 91 ] 
{
    "URI": "\/",
    "microtime": 1751074414.631783,
    "message": "MySQLBuilder built: SELECT * FROM file_access; ",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 SessionManager->init() - [\\backend\\startup.php(139)]",
        "#2 Auth::orize() - [\\backend\\Binder\\Library\\Utilities\\Session\\SessionManager.php(137)]",
        "#3 Auth::getSessionUserACL() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(67)]",
        "#4 Auth::getFileACL() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(142)]",
        "#5 SQLSet->fetchAll() - [\\backend\\Binder\\Library\\Utilities\\Traits\\FileAccessFunctions.php(31)]",
        "#6 Database->read() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(149)]",
        "#7 MySQLBuilder::buildSelect() - [\\backend\\Binder\\Library\\SQL\\Database.php(102)]",
        "#8 Log::checkpoint() - [\\backend\\Binder\\Library\\SQL\\Builders\\MySQLBuilder.php(91)]"
    ]
}

[ 2025-07-27 20:33:34 ]
Logged from: \backend\Binder\Library\SQL\Builders\MySQLBuilder.php [ Line #: 91 ] 
{
    "URI": "\/",
    "microtime": 1751074414.940071,
    "message": "MySQLBuilder built: SELECT * FROM file_access; ",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 SessionManager->init() - [\\backend\\startup.php(139)]",
        "#2 Auth::orize() - [\\backend\\Binder\\Library\\Utilities\\Session\\SessionManager.php(137)]",
        "#3 Auth::getSessionUserACL() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(67)]",
        "#4 Auth::getFileACL() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(142)]",
        "#5 Auth::filesByGroupAndType() - [\\backend\\Binder\\Library\\Utilities\\Traits\\FileAccessFunctions.php(46)]",
        "#6 SQLSet->where() - [\\backend\\Binder\\Library\\Utilities\\Traits\\FileAccessFunctions.php(113)]",
        "#7 SQLSet->fetchAll() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(133)]",
        "#8 Database->read() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(149)]",
        "#9 MySQLBuilder::buildSelect() - [\\backend\\Binder\\Library\\SQL\\Database.php(102)]",
        "#10 Log::checkpoint() - [\\backend\\Binder\\Library\\SQL\\Builders\\MySQLBuilder.php(91)]"
    ]
}

[ 2025-07-27 20:33:35 ]
Logged from: \backend\Binder\Library\SQL\Builders\MySQLBuilder.php [ Line #: 91 ] 
{
    "URI": "\/",
    "microtime": 1751074415.214043,
    "message": "MySQLBuilder built: SELECT * FROM file_access; ",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 SessionManager->init() - [\\backend\\startup.php(139)]",
        "#2 Auth::orize() - [\\backend\\Binder\\Library\\Utilities\\Session\\SessionManager.php(137)]",
        "#3 Auth::getSessionUserACL() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(67)]",
        "#4 Auth::getFileACL() - [\\backend\\Binder\\Library\\Utilities\\Session\\Auth.php(142)]",
        "#5 Auth::filesByGroupAndType() - [\\backend\\Binder\\Library\\Utilities\\Traits\\FileAccessFunctions.php(46)]",
        "#6 SQLSet->fetchAll() - [\\backend\\Binder\\Library\\Utilities\\Traits\\FileAccessFunctions.php(119)]",
        "#7 Database->read() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(149)]",
        "#8 MySQLBuilder::buildSelect() - [\\backend\\Binder\\Library\\SQL\\Database.php(102)]",
        "#9 Log::checkpoint() - [\\backend\\Binder\\Library\\SQL\\Builders\\MySQLBuilder.php(91)]"
    ]
}

[ 2025-07-27 20:33:36 ]
Logged from: \backend\startup.php [ Line #: 37 ] 
{
    "URI": "\/index.php\/user\/index\/right",
    "microtime": 1751074416.61995,
    "message": "startup user\/index\/right",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 Log::checkpoint() - [\\backend\\startup.php(37)]"
    ]
}

[ 2025-07-27 20:33:36 ]
Logged from: \backend\Binder\Controller\IndexController.php [ Line #: 75 ] 
{
    "URI": "\/index.php\/user\/index\/right",
    "microtime": 1751074416.635348,
    "message": "IndexController right",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 require() - [\\backend\\startup.php(78)]",
        "#2 IndexController->right() - [\\backend\\api.php(29)]",
        "#3 Log::checkpoint() - [\\backend\\Binder\\Controller\\IndexController.php(75)]"
    ]
}

[ 2025-07-27 20:33:36 ]
Logged from: \backend\startup.php [ Line #: 37 ] 
{
    "URI": "\/index.php\/user\/index\/left",
    "microtime": 1751074416.812258,
    "message": "startup user\/index\/left",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 Log::checkpoint() - [\\backend\\startup.php(37)]"
    ]
}

[ 2025-07-27 20:33:36 ]
Logged from: \backend\startup.php [ Line #: 37 ] 
{
    "URI": "\/index.php\/user\/index\/menus",
    "microtime": 1751074416.818319,
    "message": "startup user\/index\/menus",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 Log::checkpoint() - [\\backend\\startup.php(37)]"
    ]
}

[ 2025-07-27 20:33:36 ]
Logged from: \backend\startup.php [ Line #: 37 ] 
{
    "URI": "\/index.php\/user\/index\/contextmenu",
    "microtime": 1751074416.818431,
    "message": "startup user\/index\/contextmenu",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 Log::checkpoint() - [\\backend\\startup.php(37)]"
    ]
}

[ 2025-07-27 20:33:36 ]
Logged from: \backend\startup.php [ Line #: 37 ] 
{
    "URI": "\/index.php\/user\/index\/content",
    "microtime": 1751074416.819165,
    "message": "startup user\/index\/content",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 Log::checkpoint() - [\\backend\\startup.php(37)]"
    ]
}

[ 2025-07-27 20:33:36 ]
Logged from: \backend\Binder\Controller\IndexController.php [ Line #: 45 ] 
{
    "URI": "\/index.php\/user\/index\/left",
    "microtime": 1751074416.832717,
    "message": "IndexController left\/",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 require() - [\\backend\\startup.php(78)]",
        "#2 IndexController->left() - [\\backend\\api.php(29)]",
        "#3 Log::checkpoint() - [\\backend\\Binder\\Controller\\IndexController.php(45)]"
    ]
}

[ 2025-07-27 20:33:36 ]
Logged from: \backend\Binder\Controller\IndexController.php [ Line #: 18 ] 
{
    "URI": "\/index.php\/user\/index\/menus",
    "microtime": 1751074416.853698,
    "message": "IndexController menus",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 require() - [\\backend\\startup.php(78)]",
        "#2 IndexController->menus() - [\\backend\\api.php(29)]",
        "#3 Log::checkpoint() - [\\backend\\Binder\\Controller\\IndexController.php(18)]"
    ]
}

[ 2025-07-27 20:33:36 ]
Logged from: \backend\Binder\Library\SQL\SQLSet.php [ Line #: 115 ] 
{
    "URI": "\/index.php\/user\/index\/menus",
    "microtime": 1751074416.880167,
    "message": "[SQLSet::where() before query runs",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 require() - [\\backend\\startup.php(78)]",
        "#2 IndexController->menus() - [\\backend\\api.php(29)]",
        "#3 Page::navigation() - [\\backend\\Binder\\Controller\\IndexController.php(22)]",
        "#4 SQLSet->where() - [\\backend\\Binder\\Model\\Page.php(118)]",
        "#5 Log::checkpoint() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(115)]"
    ]
}

[ 2025-07-27 20:33:36 ]
Logged from: \backend\Binder\Library\SQL\Builders\MySQLBuilder.php [ Line #: 91 ] 
{
    "URI": "\/index.php\/user\/index\/menus",
    "microtime": 1751074416.881267,
    "message": "MySQLBuilder built: SELECT * FROM page_table; ",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 require() - [\\backend\\startup.php(78)]",
        "#2 IndexController->menus() - [\\backend\\api.php(29)]",
        "#3 Page::navigation() - [\\backend\\Binder\\Controller\\IndexController.php(22)]",
        "#4 SQLSet->where() - [\\backend\\Binder\\Model\\Page.php(118)]",
        "#5 SQLSet->fetchAll() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(133)]",
        "#6 Database->read() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(149)]",
        "#7 MySQLBuilder::buildSelect() - [\\backend\\Binder\\Library\\SQL\\Database.php(102)]",
        "#8 Log::checkpoint() - [\\backend\\Binder\\Library\\SQL\\Builders\\MySQLBuilder.php(91)]"
    ]
}

[ 2025-07-27 20:33:36 ]
Logged from: \backend\Binder\Library\SQL\SQLSet.php [ Line #: 140 ] 
{
    "URI": "\/index.php\/user\/index\/menus",
    "microtime": 1751074416.919565,
    "message": "[SQLSet::where() after query runs",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 require() - [\\backend\\startup.php(78)]",
        "#2 IndexController->menus() - [\\backend\\api.php(29)]",
        "#3 Page::navigation() - [\\backend\\Binder\\Controller\\IndexController.php(22)]",
        "#4 SQLSet->where() - [\\backend\\Binder\\Model\\Page.php(118)]",
        "#5 Log::checkpoint() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(140)]"
    ]
}

[ 2025-07-27 20:33:36 ]
Logged from: \backend\Binder\Controller\IndexController.php [ Line #: 34 ] 
{
    "URI": "\/index.php\/user\/index\/content",
    "microtime": 1751074416.964623,
    "message": "IndexController content\/",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 require() - [\\backend\\startup.php(78)]",
        "#2 IndexController->content() - [\\backend\\api.php(29)]",
        "#3 Log::checkpoint() - [\\backend\\Binder\\Controller\\IndexController.php(34)]"
    ]
}

[ 2025-07-27 20:33:36 ]
Logged from: \backend\Binder\Library\SQL\Builders\MySQLBuilder.php [ Line #: 91 ] 
{
    "URI": "\/index.php\/user\/index\/content",
    "microtime": 1751074416.991236,
    "message": "MySQLBuilder built: SELECT * FROM page_table; ",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 require() - [\\backend\\startup.php(78)]",
        "#2 IndexController->content() - [\\backend\\api.php(29)]",
        "#3 Page->__construct() - [\\backend\\Binder\\Controller\\IndexController.php(39)]",
        "#4 Model->__construct() - [\\backend\\Binder\\Model\\Page.php(19)]",
        "#5 SQLSet->fetchAll() - [\\backend\\Binder\\Library\\MVC\\Model.php(27)]",
        "#6 Database->read() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(149)]",
        "#7 MySQLBuilder::buildSelect() - [\\backend\\Binder\\Library\\SQL\\Database.php(102)]",
        "#8 Log::checkpoint() - [\\backend\\Binder\\Library\\SQL\\Builders\\MySQLBuilder.php(91)]"
    ]
}

[ 2025-07-27 20:33:37 ]
Logged from: \backend\Binder\Library\SQL\SQLSet.php [ Line #: 115 ] 
{
    "URI": "\/index.php\/user\/index\/content",
    "microtime": 1751074417.023983,
    "message": "[SQLSet::where() before query runs",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 require() - [\\backend\\startup.php(78)]",
        "#2 IndexController->content() - [\\backend\\api.php(29)]",
        "#3 Page->__construct() - [\\backend\\Binder\\Controller\\IndexController.php(39)]",
        "#4 Model->__construct() - [\\backend\\Binder\\Model\\Page.php(19)]",
        "#5 SQLSet->where() - [\\backend\\Binder\\Library\\MVC\\Model.php(28)]",
        "#6 Log::checkpoint() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(115)]"
    ]
}

[ 2025-07-27 20:33:37 ]
Logged from: \backend\Binder\Library\SQL\Builders\MySQLBuilder.php [ Line #: 91 ] 
{
    "URI": "\/index.php\/user\/index\/content",
    "microtime": 1751074417.041374,
    "message": "MySQLBuilder built: SELECT * FROM page_log; ",
    "backtrace": [
        "#0 require() - [\\index.php(1)]",
        "#1 require() - [\\backend\\startup.php(78)]",
        "#2 IndexController->content() - [\\backend\\api.php(29)]",
        "#3 Controller->view() - [\\backend\\Binder\\Controller\\IndexController.php(39)]",
        "#4 View->__construct() - [\\backend\\Binder\\Library\\MVC\\Controller.php(66)]",
        "#5 require() - [\\backend\\Binder\\Library\\MVC\\View.php(16)]",
        "#6 Page->__toString() - [\\backend\\Binder\\View\\Index\\content.php(6)]",
        "#7 SQLSet->saveChanges() - [\\backend\\Binder\\Model\\Page.php(107)]",
        "#8 SQLSet->commitChanges() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(213)]",
        "#9 SQLSet->where() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(83)]",
        "#10 SQLSet->fetchAll() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(133)]",
        "#11 Database->read() - [\\backend\\Binder\\Library\\SQL\\SQLSet.php(149)]",
        "#12 MySQLBuilder::buildSelect() - [\\backend\\Binder\\Library\\SQL\\Database.php(102)]",
        "#13 Log::checkpoint() - [\\backend\\Binder\\Library\\SQL\\Builders\\MySQLBuilder.php(91)]"
    ]
}

```