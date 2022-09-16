<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>latihan 1</title>
    <link rel="stylesheet" href="DataTables/datatables.min.css">
</head>
<body>
    <table id="contoh" class="display">
        <thead>
            <tr>
                <th width="5%">No</th>
                <th width="12%">Nama</th>
                <th width="15%">Kelas</th>
                <th width="15%">Alamat</th>
                <th width="5%">No HP</th>
            </tr>
            <tr>
                <td>3</td>
                <td>ugi/td>
                <td>XII k1</td>
                <td>dago pakar</td>
                <td>087892387652</td>
             </tr>  
            <tr>
                <td>3</td>
                <td>ugi</td>
                <td>XII k1</td>
                <td>dago pakar</td>
                <td>087892387652</td>
            </tr>
        </thead>
    </table>
<script src="DataTables/jQuery-3.6.0/jquery-3.6.0.min.js"></script>
<script src="DataTables/datatables.min.js"></script>
<script>
    $(function(){
        //  var data = [
        // ["1", "ahmad", "XII RPL 1","dagopakar", "087892387652"]
        // ["1", "sugiarto", "XII RPL 1","dagopakar", "087892387652"]
        // ];
        var data = [];

        for (let i = 0; i <5;j++){
            data.push([i]);
                data[i].push[j];
        }
        $("#contoh").DataTable({
            responsive : true
        });
    });
</script>
</body>
</html># datatable
