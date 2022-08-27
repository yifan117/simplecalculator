<script lang="ts">

// // export let console: string;

// // function setValue(value: string) {

// // console += value;
// }
</script>

<div class="calcbody">
    <div class="row">
        <div class="operationTop">C</div>
        <div class="operationTop">+/-</div>
        <div class="operationTop">%</div>
        <div class="operationSign">÷</div>
    </div>
    <div class="row">
        <div class="digits">7</div>
        <div class="digits">8</div>
        <div class="digits">9</div>
        <div class="operationSign">×</div>
    </div>
    <div class="row">
        <div class="digits">4</div>
        <div class="digits">5</div>
        <div class="digits">6</div>
        <div class="operationSign">-</div>
    </div>
    <div class="row">
        <div class="digits">1</div>
        <div class="digits">2</div>
        <div class="digits">3</div>
        <div class="operationSign">+</div>
    </div>
    <div class="row">
        <div class="zero">0</div>
        <div class="digits">.</div>
        <div class="operationSign">=</div>
    </div>
</div>

<style>

.row {
    gap: 8px;
    padding: 3px;
    display: flex;
}

.digits {

    width: 45px;
    height: 45px;
    font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    padding: 3px;
    text-align: center;
    background-color: #555555;
    display: flex;
    justify-content: center;
    flex-direction: column;
    border-radius: 40px;
    color: #ffffff;

}

.digits:hover {
    background-color: #ffffff;
    opacity: 55%;
    color: #000000;
    cursor: pointer;
}

.zero {
    width: 104px;
    height: 45px;
    border-radius: 40px;
    font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    background-color: #555555;
    text-align: center;
    display: flex;
    justify-content: center;
    flex-direction: column;
    padding: 3px;
    color: #ffffff;
}

.zero:hover {
    background-color: #ffffff;
    opacity: 55%;
    color: #000000;
    cursor: pointer;
}

.operationSign {
    width: 45px;
    height: 45px;
    font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    padding: 3px;
    text-align: center;
    background-color: #ec9006;
    display: flex;
    justify-content: center;
    flex-direction: column;
    border-radius: 40px;
    color: #ffffff;
}

.operationSign:hover {
    background-color: #f5c77e;
    opacity: 80%;
    color: #000000;
    cursor: pointer;
}

.operationTop {
    width: 45px;
    height: 45px;
    font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    padding: 3px;
    text-align: center;
    background-color: #A9A9A9;
    display: flex;
    justify-content: center;
    flex-direction: column;
    border-radius: 40px;
}

.operationTop:hover {
    background-color: #888888;
    opacity: 80%;
    color: #ffffff;
    cursor: pointer;
}

.calcbody {
    height: 287px;
    width: 228px;
    background-color: #000000;
    padding: 10px;
    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 10px;
}

</style>