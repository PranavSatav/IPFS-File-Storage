# IPFS-File-Storage
Requirements - https://nodejs.org/en/download/

node -v //retrieves the nodejs version


Step 1 : npx create-react-app demo

Step 2 : cd demo

Step 3 : code .

Step 4 : app.js >>


    // MultipleFilesUpload Component : Uploads Multiple files to IPFS and returns the URL
    import React, { useState } from 'react'
    import { MultipleFilesUpload } from 'react-ipfs-uploader'

    const App = () => {
    const [multipleFilesUrl, setMultipleFilesUrl] = useState('')

    return (
        <div>
            <MultipleFilesUpload setUrl={setMultipleFilesUrl} />
            MultipleFilesUrl : <a
                href={multipleFilesUrl}
                target='_blank'
                rel='noopener noreferrer'
            >
                {multipleFilesUrl}
            </a>
        </div>
    )
    }

    export default App


Step 5 : yarn start
