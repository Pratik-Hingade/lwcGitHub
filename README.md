<template>
    <lightning-card title="Calculator">    
            <lightning-input type='number' label='First No' value={fNo} onchange={firsthandleChange} class="slds-p-left_x-large slds-p-right_x-large"></lightning-input>
            <lightning-input type='number' label='Second NO' value={sNo} onchange={secondhandleChange} class="slds-p-left_x-large slds-p-right_x-large"></lightning-input>
<div class="slds-align_absolute-center">
<lightning-button class="slds-p-top_x-small slds-p-left_x-large" variant='Success' label='Add' title='title' onclick={handleAdd}></lightning-button>
<lightning-button class="slds-p-top_x-small slds-p-left_x-large" variant='Destructive' label='Sub' title='title' onclick={handleSub}></lightning-button>
<lightning-button class="slds-p-top_x-small slds-p-left_x-large" variant='brand' label='Multi' title='title' onclick={handleMulti}></lightning-button>
<lightning-button class="slds-p-top_x-small slds-p-left_x-large" variant='brand-outline' label='Div' title='title' onclick={handleDiv}></lightning-button>
</div>
<b><i>
    Result:-{result}
</b> </i>
    </lightning-card>
</template>
