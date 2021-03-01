https://developers.google.com/books/docs/v1/using#WorkingVolumes

intitle: Returns results where the text following this keyword is found in the title. inauthor: Returns results where the text following this keyword is found in the author. inpublisher: Returns results where the text following this keyword is found in the publisher. subject: Returns results where the text following this keyword is listed in the category list of the volume. isbn: Returns results where the text following this keyword is the ISBN number. lccn: Returns results where the text following this keyword is the Library of Congress Control Number. oclc: Returns results where the text following this keyword is the Online Computer Library Center number.

Filtering You can use the filter parameter to restrict the returned results further by setting it the to one of the following values:

partial - Returns results where at least parts of the text are previewable. full - Only returns results where all of the text is viewable. free-ebooks - Only returns results that are free Google eBooks. paid-ebooks - Only returns results that are Google eBooks with a price. ebooks - Only returns results that are Google eBooks, paid or free. Examples of non-eBooks would be publisher content that is available in limited preview and not for sale, or magazines.

Pagination You can paginate the volumes list by specifying two values in the parameters for the request:

startIndex - The position in the collection at which to start. The index of the first item is 0. maxResults - The maximum number of results to return. The default is 10, and the maximum allowable value is 40. Print Type You can use the printType parameter to restrict the returned results to a specific print or publication type by setting it to one of the following values:

all - Does not restrict by print type (default). books - Returns only results that are books. magazines - Returns results that are magazines.

Sorting

relevance - Returns results in order of the relevance of search terms (this is the default). newest - Returns results in order of most recently to least recently published.
