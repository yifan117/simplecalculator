<script lang="ts">

// // export let console: string;

// // function setValue(value: string) {

// // console += value;
// }
</script>

<div class="calcbody">
    <div class="row4">
        <div class="clearsign">C</div>
        <div class="changepl">+/-</div>
        <div class="percent">%</div>
        <div class="dividesign">÷</div>
    </div>
    <div class="row3">
        <div class="digits">7</div>
        <div class="digits">8</div>
        <div class="digits">9</div>
        <div class="multiplysign">×</div>
    </div>
    <div class="row2">
        <div class="digits">4</div>
        <div class="digits">5</div>
        <div class="digits">6</div>
        <div class="minussign">-</div>
    </div>
    <div class="row1">
        <div class="digits">1</div>
        <div class="digits">2</div>
        <div class="digits">3</div>
        <div class="plussign">+</div>
    </div>
    <div class="row0">
        <div class="zero">0</div>
        <div class="decimal">.</div>
        <div class="equalsign">=</div>
    </div>
</div>

<style>

.row0 {
    gap: 8px;
    padding: 3px;
    display: flex;
}

.row1 {
    gap: 8px;
    padding: 3px;
    display: flex;

}

.row2 {
    gap: 8px;
    padding: 3px;
    display: flex;
}

.row3 {
    gap: 8px;
    padding: 3px;
    display: flex;
}

.row4 {
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

.decimal {
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

.decimal:hover {
    background-color: #ffffff;
    opacity: 55%;
    color: #000000;
    cursor: pointer;
}

.equalsign {
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

.equalsign:hover {
    background-color: #f5c77e;
    opacity: 80%;
    color: #000000;
    cursor: pointer;
}

.plussign {
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

.plussign:hover {
    background-color: #f5c77e;
    opacity: 80%;
    color: #000000;
    cursor: pointer;
}

.minussign {
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

.minussign:hover {
    background-color: #f5c77e;
    opacity: 80%;
    color: #000000;
    cursor: pointer;
}

.multiplysign {
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

.multiplysign:hover {
    background-color: #f5c77e;
    opacity: 80%;
    color: #000000;
    cursor: pointer;
}

.dividesign {
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

.dividesign:hover {
    background-color: #f5c77e;
    opacity: 80%;
    color: #000000;
    cursor: pointer;
}

.percent {
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

.percent:hover {
    background-color: #888888;
    opacity: 80%;
    color: #ffffff;
    cursor: pointer;
}

.changepl {
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

.changepl:hover {
    background-color: #888888;
    opacity: 80%;
    color: #ffffff;
    cursor: pointer;
}

.clearsign {
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

.clearsign:hover {
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