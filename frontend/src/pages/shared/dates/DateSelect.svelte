<script lang='ts'>
    export let header = "Start";
    export let width = "auto";
</script>

<div style="width: {width}">
    <h3>
        {header}
    </h3>
    <input type="datetime-local" id="dateInput-from" min="2022-01-01" max="2099-01-01">
</div>

<style>
    /* div {
        border: 1px solid red;
    } */
    h3 {
        margin-top: 0;
        margin-bottom: 10px;
    }
    input {
        cursor: pointer;
        border-radius: 10px;
        border: none;
        padding: 3px 10px;
        font-size: 11pt;
        background-color: #162a37;
        border: 2px solid transparent;
        background: linear-gradient(#12232E, #12232E) padding-box,
                    linear-gradient(45deg, #1c9bab 0%, #0e6764) border-box;
        filter: drop-shadow(0px 10px 5px rgba(0, 0, 0, 0.3));                    
    }
    input:focus {
        outline: none;
        border: 2px solid #ce4820;
    }
    @media (min-width: 1000px) {
        input {
            font-size: 12pt;
        }
    }
</style>