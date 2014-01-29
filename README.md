pivotal-tracker-api
===================

Library that provides a PHP interface to interact with the PivotalTracker API V5


Example:

$pivotTracker =  new \PivotalTracker\Client(  $apiToken , $projectId ) ;

print_R( $pivotTracker->getStories( 'label:mylabel') ) ;

