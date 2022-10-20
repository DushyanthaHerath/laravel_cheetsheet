Store Json in Storage->Public Folder

Storage::disk('public')->put('images.json', json_encode($data));
