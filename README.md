unzip -o AnimalAdoption_changed_files_4_hindi.zip
rm AnimalAdoption_changed_files_4_hindi.zip
mbt build
cf deploy mta_archives/animaladoption-test_1.0.0.mtar
